<template>
    <div class="secondSection">
        <div class="container">
             <div class=" header">
                <NumberCard number="1" />
                <p class="header-title">Welche Produkte wollen sie digitalisieren?</p>
             </div>
        </div>
    </div>
</template>

<script>
import NumberCard from "@/components/tools/NumberCard.vue";
export default {
    components: {
        NumberCard,
    },
    
}
</script>



<style scoped>
    .secondSection {
        background-color: #FFFFFF;
        width: 100%;
        display: flex;
        padding: 50px 0px;
    }
    .container {
        margin: auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 5px;
        width: 100%;
    }
    .header {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .header-title {
        font-size: 55px;
        font-weight: 700;
        color: #02303B;
        font-family: Inter;
        text-align: center;
        line-height: 0px;
    }


    /* responsive */
    @media only screen and (max-width: 1160px) {
        .header-title {
            font-size: 40px;
        }
    }

    @media only screen and (max-width: 840px) {
        .header-title {
            font-size: 30px;
        }
    }

    @media only screen and (max-width: 618px) {
        .header-title {
            font-size: 25px;
        }
    }

    @media only screen and (max-width: 515px) {
        .header-title {
            font-size: 20px;
            line-height: 24px
        }
    }


</style>