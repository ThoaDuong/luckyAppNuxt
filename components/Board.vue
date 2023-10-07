<template>
    <table class="table-auto mx-auto text-center">
        <tbody class="border-2 border-gray-600">
            <tr v-for="(row, rowIndex) in props.boardNumber">
                <td v-for="number in row"
                    @click="handleClickSquare(number)"
                    :key="number"
                    :style="{'background': number !== null ? props.color : 'rgb(212 212 216)'}"
                    :class="{
                        'relative': true,
                        'text-white text-lg border px-2 py-3 hover:cursor-pointer': number !== null,
                        'text-lg border px-4 py-3': number === null,
                        'px-3': number && number < 10,
                    }"
                    >
                    <span>{{ number }}</span>
                    <span v-if="activeBoard[rowIndex].indexOf(number) !== -1" class="absolute top-6 left-0.5 border-t-2 rotate-45 border-gray-500 px-4"></span>
                    <span v-if="activeBoard[rowIndex].indexOf(number) !== -1" class="absolute top-6 left-0.5 border-t-2 rotate-[-45deg] border-gray-500 px-4"></span>
                </td>
            </tr>
        </tbody>
    </table>
</template>
<script setup>
    import Swal from 'sweetalert2'
    const props = defineProps(['boardNumber', 'calledNumbers', 'color']);
    const activeBoard = ref(new Array( [], [], [], [], [], [], [], [], []));

    function handleClickSquare(calledNumber){
        if(!calledNumber){
            return null;
        }
        props.boardNumber.map((row, rowIndex) => {
            row.map(number => {
                if(number === calledNumber){
                    let tempActiveBoard = activeBoard.value[rowIndex];
                    let index = tempActiveBoard.indexOf(number);
                    index === -1 ? handleAddNumber(tempActiveBoard, number) : handleRemoveNumber(tempActiveBoard, index);
                }
            })  
        })
    }

    function handleAddNumber(tempActiveBoard, number){
        if(tempActiveBoard.length < 4){
            tempActiveBoard.push(number);
        }else{
            checkWinGame(tempActiveBoard, number);
        }
    }

    function handleRemoveNumber(tempActiveBoard, index){
        tempActiveBoard.splice(index, 1);
    }

    function clearActiveBoard(){
        activeBoard.value = new Array( [], [], [], [], [], [], [], [], []);                 
    }

    function  alertWinGame(){
        Swal.fire({
            title: 'Bingo!',
            text: 'Congratulations! You won.',
            icon: 'success',
            confirmButtonText: 'End Game'
        })
    }
    
    function  alertInValidWinGame(missingNumbers){
        Swal.fire({
            title: 'Oh no!',
            text: `Misunderstanding! The numbers: ${missingNumbers.toString()} have not being called`,
            icon: 'error',
            confirmButtonText: 'Continue'
        })
    }

    function checkWinGame(tempActiveBoard, number){
        //check all number is called
        let missingNumbers = [];
        props.calledNumbers.indexOf(number) ? missingNumbers.push(number) : null;
        tempActiveBoard.forEach(numberActive => {
            let index = props.calledNumbers.indexOf(numberActive);
            if(index === -1){
                missingNumbers.push(numberActive);
            }
        })
        //is valid win game
        if(missingNumbers.length > 0){
            alertInValidWinGame(missingNumbers);
        }else{
            alertWinGame();
            clearActiveBoard();
        }
    }
</script>