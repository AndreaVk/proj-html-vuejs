<template>
    <main>
        <div class="square">
            <Square />
        </div>
        <div class="part1">
            <Part1/>
        </div>
        
        <div class="part2">
            <Part2/>
        </div>
        <div class="Part3">
            <Part3/>
        </div>
        <div class="part4">
            <Part4/>
        </div>
        <div class="part5">
            <Part5/>
        </div>
    </main>
</template>

<script>
import Square from '../elements/Square.vue';
import Part1 from '../elements/Part1.vue';
import Part2 from '../elements/Part2.vue';
import Part3 from '../elements/Part3.vue';
import Part4 from '../elements/Part4.vue';
import Part5 from '../elements/Part5.vue';
export default {
    name:'Main',
    components:{
        Square,
        Part1,
        Part2,
        Part3,
        Part4,
        Part5, 
    }
}
</script>

<style>

</style>