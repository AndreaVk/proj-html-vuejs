<template>
    <header>
        <div>
            <div>
                <div class="carousel-item active">
                    <img class="d-block w-100 h-100" src="../../assets/images/h5-slide-2-background.jpg" alt="">
                </div>
            </div>
        </div>
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
        cursor: pointer;
    }
    .container{
        position: sticky;
        z-index: 10;
        
    }
    header{
        height: 850px;
    }
    .carousel-item{
        min-height: 800px;
        background-size: cover;
        background-repeat: no-repeat;
    }
</style>