<template>
    <header>
        <div class="container">
            <div class="row align-items center" id="fix">
                <div class="left col-4">
                    <img src="../../assets/images/logo-light.png" alt="">
                </div>
                <div class="right col-8">
                    <NavBar />
                </div>
            </div>
            <div class="text">
                <h1>Accelerate Your Career</h1>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Odit, iure? Et qui minima facilis ullam saepe dignissimos. Facere illo dicta cupiditate dignissimos. Nulla deserunt fuga corporis inventore laudantium reiciendis qui!</p>
                <button>Register Now</button>
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
    #fix{
        z-index: 10;
        position: sticky;
        
    }
    header{
        height: 850px;
        background-image: url('../../assets/images/h5-slide-1-background.jpg');
    }
    .text{
        text-align: center;
        margin-top: 20%;
    }
    h1,
    p{
        color: white;
    }
    h1{
        font-size: 80px;
    }
    p{
        font-size: 20px;
    }
    button{
        background-color:#00AFFF ;
        border: 1px solid #00AFFF;
        color: white;
        font-weight: bold;
        padding: 14px 36px;
        margin-top: 32px;
    }
</style>