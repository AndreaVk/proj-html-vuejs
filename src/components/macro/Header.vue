<template>
    <header>
        <div class="container">
            <div class="row align-items center">
                <div class="left col-4">
                    <img src="../../assets/images/logo-light.png" alt="">
                </div>
                <div class="right col-8">
                    <NavBar />
                </div>
            </div>
            
        </div>
    </header>
    
</template>

<script>
import NavBar from '../elements/NavBar.vue';
export default {
    name:'Header',
    components: {
        NavBar,
    }
    
}
</script>

<style lang="scss" scoped>
    .left{
        margin-top: 30px;
    }
    img{
        height: 32px;
    }
    header{
        position: sticky;
        z-index: 10;
    }
</style>