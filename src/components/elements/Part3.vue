<template>
    <div id="carouselExampleControls" class="carousel slide text-center justify-content-center" data-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img class="slide" src="../../assets/images/testimonials-standard-1.png" alt="First slide">
                <p>"Nroim gravida nibh vel velit auctor aliquetn sollicitudirem quibibendum auci elit cons equat ipsutis sem nibh id elit. Duis sed odio sit amet nibh vulputate cursus a sit amet mauris. Morbi accumsan ipsum velit. Nam nec tellus"</p>
                <h3>Virginia Foster</h3>
                <h5>Student</h5>
            </div>
            <div class="carousel-item">
                <img class="slide" src="../../assets/images/testimonials-standard-2.png" alt="Second slide">
                <p>"Nroim gravida nibh vel velit auctor aliquetn sollicitudirem quibibendum auci elit cons equat ipsutis sem nibh id elit. Duis sed odio sit amet nibh vulputate cursus a sit amet mauris. Morbi accumsan ipsum velit. Nam nec tellus"</p>
                <h3>Joan Collins</h3>
                <h5>Student</h5>
            </div>
            <div class="carousel-item">
                <img class="slide" src="../../assets/images/testimonials-standard-3.png" alt="Third slide">
                <p>"Nroim gravida nibh vel velit auctor aliquetn sollicitudirem quibibendum auci elit cons equat ipsutis sem nibh id elit. Duis sed odio sit amet nibh vulputate cursus a sit amet mauris. Morbi accumsan ipsum velit. Nam nec tellus"</p>
                <h3>Victor Green</h3>
                <h5>Teacher</h5>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
</template>

<script>

</script>

<style lang='scss' scoped>
    #carouselExampleControls{
        background-image: url('../../assets/images/h5-parallax-img-1.png');
        height: 650px;
        width: 100%;
        z-index: 1;
    }

    .carousel-item{
        color: white;
        width: 30%;
        margin-left: 680px;
        margin-top: 190px;
    }
    p{
        font-size: 16px;
        margin-top: 25px;
    }
    h3{
        font-size: 25px;
        margin-top: 35px;
    }

    h5{
        font-size: 18px;
    }
</style>