<template>
    <main>
        <div class="square">
            <Square />
        </div>
        <div class="part1">
            <Part1/>
        </div>
    </main>
</template>

<script>
import Square from '../elements/Square.vue';
import Part1 from '../elements/Part1.vue';
export default {
    name:'Main',
    components:{
        Square,
        Part1,
    }
}
</script>

<style>

</style>