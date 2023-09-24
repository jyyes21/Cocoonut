<template>
    <div class="bg-white w-full pb-[15vh]">
        <div class="flex w-full justify-center">
            <p class="font-[600] text-[30px] py-[12vh]">TENDANCES</p>
        </div>
        <div class="grid lg:grid-cols-4 sm:grid-cols-3 grid-cols-1 gap-x-5 gap-y-20 w-5/6 mx-auto">

       <TendancesCards />


        </div>
    </div>
</template>

<script setup>
import TendancesCards from './TendancesCards.vue';

</script>

