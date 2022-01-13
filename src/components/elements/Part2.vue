<template>
    <div class="part2">
        <div class="img col-7">
            <img src="../../assets/images/h5-img-2.jpg" alt="">
        </div>
        <div class="info col-5">
            <div class="text">
                <h2>Empowering Children to reach Their Potential.</h2>
                <p>Lorem ipsum gravida nibh vel velit auctor aliquetnean sollicitudin, lorem quis bibendum auci elit consequat ipsutis sem nibh id eis sed odio sit amet nibh vulputate.</p>
            </div>
            <div class="dati">
                <div class="num">
                <h5>168</h5>
                <span>User Stories</span>
            </div>
            <div class="num">    
                <h5>347</h5>
                <span>Events</span>
            </div>
            </div>
            
        </div>
        
    </div>

    
</template>

<script>
export default {
    name:'Part2',
}
</script>

<style lang="scss" scoped>
    .part2{
        width: 70%;
        display: flex;
        margin: 0 auto;
        margin-top: 50px;
        justify-content: space-around;
        align-items: center;
    }

    img{
        width: 100%;
    }
    h2{
        font-size: 45px;
    }
    p{
        font-size: 16px;
        color: #707070;
        margin-top: 20px;
        margin-bottom: 25px;
        width: 85%;
    }
    
    .dati{
        margin: 0 auto;
        display: flex;
        align-items:flex-start ;
        margin-top: 50px;
        width: 100%;

    }

    .num{
        display: flex;
        align-items: flex-start;
        flex-direction: column;
        color:#00AFFF;
        margin-right: 85px;
        
    }
    h5{
        font-size: 48px;
    }
    span{
        font-size: 21px;
    }
</style>