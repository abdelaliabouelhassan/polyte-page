<template>
    
        <div class="numberCard">
            <div class="number">
                {{number}}
            </div>
        </div>
</template>

<script>
export default {
    props:{
        number: {
            type: Number,
            required: true
        },
    }
}
</script>

<style scoped>
    .numberCard {
        background: #02303B26 0% 0% no-repeat padding-box;
        width: 138px;
        height: 138px;
        display: flex;
        justify-content: center;
        border: 6px solid #02303B;
        border-radius: 35px;
        opacity: 0.5;
    }
    .number {
        font-size: 90px;
        font-weight: 700;
        color: #02303B;
        font-family: Inter;
        margin: auto;
    }
    /* responsive */

    @media only screen and (max-width: 1160px) {
        .numberCard {
            width: 100px;
            height: 100px;
        }
        .number {
            font-size: 60px;
        }
    }

    @media only screen and (max-width: 840px) {
        .numberCard {
            width: 80px;
            height: 80px;
        }
        .number {
            font-size: 50px;
        }
    }

    




</style>