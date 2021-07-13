<template>
 <div>
     Counter: {{ number }}
     <div>
        <label for="counter">Counter: </label>
        <input type="text" v-model="number" />
        <button v-on:click="increase">+</button>
        <button v-on:click="decrease">-</button>
        <button v-on:click="increaseByTen">+10</button>
        <button v-on:click="timesTwo">x2</button>
     </div>
 </div>
</template>

<script>
export default {
    data(){
        return{
            number: 10
        }
    },
    methods:{
        increase(){
            this.number++;
        },
        decrease(){
            this.number--;
        },
        increaseByTen(){
            this.number+=10;
        },
        timesTwo(){
            this.number*=2;
        }
    },
};
</script>

<style lang = "scss" scoped>

</style>