<template>
    <div class="squares">
        <div class="square">
            <img src="../../assets/images/h5-custom-icon-1.png" alt="">
            <h2>Languages</h2>
        </div>
        <div class="square">
            <img src="../../assets/images/h5-custom-icon-2.png" alt="">
            <h2>Software</h2>
        </div>
        <div class="square">
            <img src="../../assets/images/h5-custom-icon-3.png" alt="">
            <h2>Business</h2>
        </div>
        <div class="square">
            <img src="../../assets/images/h5-custom-icon-4.png" alt="">
            <h2>Chemisty</h2>
        </div>
        <div class="square">
            <img src="../../assets/images/h5-custom-icon-5.png" alt="">
            <h2>Science</h2>
        </div>
        <div class="square">
            <img src="../../assets/images/h5-custom-icon-6.png" alt="">
            <h2>DIY&Craft</h2>
        </div>
        
    </div>
</template>

<script>
export default {
    name:'Square',
}
</script>

<style lang="scss" scoped>
    .squares{
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: 50px;
        width: 70%;
    }
    .square{
        background-color: #F2F8FC;
        width: calc((100% / 6) - 20px);
        display: flex;
        align-items: center;
        flex-direction: column;
    }
    img{
        margin-top: 32px;
    }
    h2{
        font-size: 16px;
        margin-top: 30px;
        margin-bottom: 30px;
    }

    img:hover{
        width: 70px;
    }
</style>