<template>
    <div>
        <h2 class="p-5">Complete Your Design<br> What We Designed</h2>
        <div class="d-flex justify-content-around p-5" style="background-color: rgb(244, 244, 244);">
            <Card v-for="(item, index) in aCardTitle" :key="index" :cardTitle="item" v-bind:cardImg="aCardImg[index]"
                :cardPrice="aCardPrice[index]"></Card>
            <!-- <Card :cardImg="'chair-1'" :cardTitle="'Samman Kakka'" :cardPrice="'10.000.000'"></Card> -->
        </div>
    </div>
</template>
<script>
import Card from './Card.vue';
export default {
    name: 'SliderComponent',
    components: {
        Card
    },
    data() {
        return {
            aCardImg: ['chair-1', 'chair-2', 'chair-3', 'chair-4'],
            aCardTitle: ['Cangkir Mauttle', 'Samman Kakka', 'Lino Dino', 'Syail Dorime'],
            aCardPrice: ['45.000.000', '20.000.000', '18.000.000', '28.000.000']
        }
    }
}
</script>