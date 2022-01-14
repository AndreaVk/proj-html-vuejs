<template>
    <div class="bg">
        <div class="text1">
            <h2>Popular Online Courses</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Laborum id, facere possimus repellendus libero aliquid eaque nihil assumenda nemo excepturi minima sunt praesentium corrupti dolores vitae dolor labore ipsum? Non?</p>
        </div>
        <div class="box-container">
            <div class="box">
                <img src="../../assets/images/course-11-f-img.jpg" alt="">
                <h3>Business English<span> 20$</span></h3>
                <h5>Preston Marshall</h5>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Perspiciatis commodi aliquam odit possimus id nobis mollitia fugit dolores ullam alias. Alias cumque harum, maxime consequuntur laboriosam facere unde saepe possimus.</p>

            </div>
            <div class="box">
                <img src="../../assets/images/course-9-f-img.jpg" alt="">
                <h3>Social Computing<span> 20$</span></h3>
                <h5>David Sanders</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. At, voluptas. Iure ullam, deserunt consequatur excepturi eligendi autem delectus sequi magnam, saepe in, adipisci pariatur beatae harum ipsum recusandae temporibus nobis.</p>

            </div>
            <div class="box">
                <img src="../../assets/images/course-7-f-img.jpg" alt="">
                <h3>Learn Spanish<span> 20$</span></h3>
                <h5>Jenny King</h5>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse corporis nulla fuga nobis dolorum eveniet odio perferendis nihil optio quidem laudantium, nostrum temporibus excepturi quam asperiores recusandae, exercitationem magnam consectetur?</p>

            </div>
            
        </div>
        <div class="circle">
                <i class="fas fa-circle"></i>
                <i class="fas fa-circle"></i>
                <i class="fas fa-circle"></i>
        </div> 
    </div>
</template>

<script>
export default {
    name:'Part5',
}
</script>

<style lang="scss" scoped>
    .bg{
        background-image: url('../../assets/images/page-background-img.png');
        height: 750px;
    }
    .text1{
        width: 60%;
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 0 auto;
        margin-top: 150px;
    }
    .text1 p{
        text-align: center;
        margin-top: 15px;
        color: #707070;
    }
    .text1 h2{
        font-size: 45px;
    }

    .box-container{
        width: 70%;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .box{
        width: 28%;
        margin-left: 25px;
        margin-top: 60px;
        margin-right: 25px;
        border: 1px solid #F7F9F8;
    }

    .box img{
        width: 100%;
        height: 50%;
    }

    h3, h5, p{
        margin-left: 18px;
        margin-top: 18px;
    }

    p{
        color:#707070 ;
        font-size: 15px;
    }

    h5{
        color: #707070;
        font-size: 14px;
    }

    h3{
        font-size: 22px;
    }

    span{
        margin-left: 100px;
        font-size: 13px;
        padding: 5px 20px;
        background-color: aqua;
        border-radius: 15px;
    }

    .circle{
        display: flex;
        align-items: center;
        justify-content: center;
        margin-top: 18px;
    }

    .circle i{
        margin-left: 10px;
        font-size: 13px;
        color: #9CE0FF;
        cursor: pointer;
    }

    .circle i:hover{
        color:#40C4FF ;
    }
</style>
