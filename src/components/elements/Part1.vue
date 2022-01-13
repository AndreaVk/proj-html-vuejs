<template>
    <div class="part1">
        <div class="text col-4">
            <h2>The Trusted Name for In-Home Tutoring.</h2>
            <p>Lorem ipsum gravida nibh vel velit auctor aliquetnean sollicitudin, lorem quis bibendum auci elit consequat ipsutis sem nibh id eis sed odio sit amet nibh vulputate cursus mauris.</p>
            <button>Learn More</button>
        </div>
        <div class="image col-8">
            <img src="../../assets/images/h5-img-1.jpg" alt="">
        </div>
    </div>
</template>

<script>
export default {
    name:'Part1',
}
</script>

<style lang="scss" scoped>
    .part1{
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
    }
    button{
        background-color: white;
        border: 1px solid white;
        font-weight: bold;
        font-size: 14px;
        margin-left: -8px;
        color: #00AFFF;
        text-transform: uppercase;
    }
    button:hover{
        background-color: #00AFFF;
        color: white;
        
    }
</style>