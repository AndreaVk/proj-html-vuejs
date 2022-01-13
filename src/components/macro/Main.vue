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
    </main>
</template>

<script>
import Square from '../elements/Square.vue';
import Part1 from '../elements/Part1.vue';
import Part2 from '../elements/Part2.vue';
export default {
    name:'Main',
    components:{
        Square,
        Part1,
        Part2,
    }
}
</script>

<style>

</style>