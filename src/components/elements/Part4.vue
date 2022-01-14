<template>
    <div class="row">
        <div class="col-4">
            <div class="list-group" id="list-tab" role="tablist">
                <a class="list-group-item list-group-item-action active"  id="list-home-list" data-toggle="list" href="#list-home" role="tab" aria-controls="What we do">What we do</a>
                <a class="list-group-item list-group-item-action"  id="list-profile-list" data-toggle="list" href="#list-profile" role="tab" aria-controls="Degree Programme">Degree Programme</a>
                <a class="list-group-item list-group-item-action"  id="list-messages-list" data-toggle="list" href="#list-messages" role="tab" aria-controls="Career Achievements">Career Achievements</a>
                <a class="list-group-item list-group-item-action"  id="list-settings-list" data-toggle="list" href="#list-settings" role="tab" aria-controls="Personal Managment">Personal Managment</a>
                <a class="list-group-item list-group-item-action"  id="list-messages-list" data-toggle="list" href="#list-messages" role="tab" aria-controls="Steps to Success">Steps to Success</a>
                <a class="list-group-item list-group-item-action"  id="list-settings-list" data-toggle="list" href="#list-settings" role="tab" aria-controls="Knowledge Transfer">Knowledge Transfer</a>
            </div>
        </div>
        <div class="col-8">
            <div class="tab-content" id="nav-tabContent">
                <div class="tab-pane fade show active" id="list-home" role="tabpanel" aria-labelledby="list-home-list">
                    <h2>Learning Possibilities</h2>
                    <p>Lorem ipsum gravida nibh vel velit auctor aliquetn sollicitudirem quibibendum auci elit cons equat ipsutis sem nibh id elit. Duis sed odio sit amet nibh vulputate cursus a sit amet mauris. Morbi accumsan ipsum velit. Nam nec tellus a odio tincidunt</p>
                    <div class="check-part">
                        <ul>
                            <li><i id="check" class="fas fa-check"></i>We enrich lives through learning.</li>
                            <li><i id="check" class="fas fa-check"></i>Maximizing potential through individual attention.</li>
                            <li><i id="check" class="fas fa-check"></i>The trusted name for specialized training.</li>
                            <li><i id="check" class="fas fa-check"></i>People teach. People learn. This is where they connect.</li>
                        </ul>
                        <div class="image">
                            <img src="../../assets/images/h12-tabs-icon-1.png" alt="">
                        </div>
                    </div>
                    
                </div>
                <div class="tab-pane fade show" id="list-profile" role="tabpanel" aria-labelledby="list-profile-list">Davide</div>
                <div class="tab-pane fade show" id="list-messages" role="tabpanel" aria-labelledby="list-messages-list">Luigi</div>
                <div class="tab-pane fade show" id="list-settings" role="tabpanel" aria-labelledby="list-settings-list">Milva</div>
            </div>
        </div>
    </div>
</template>

<script>

export default{
    
}
</script>

<style lang="scss" scoped>
    .row{
        width: 70%;
        margin: 0 auto;
        margin-top: 70px;
    }

    .list-group-item{
        height: 70px;
        display: flex;
        align-items: center;
    }
    p{
        margin-top: 30px;
        color: #9A9A9A;
        width: 80%;
        font-size: 18px;
    }
    h2{
        font-size: 40px;
        
    }
    ul{
        margin-top: 55px;
        margin-left: -30px;
    }
    li{
        list-style: none;
        margin-top: 20px;
        color: #9A9A9A;
    }
    #check{
        color:#00AFFF ;
        margin-right: 9px;
    }

    .check-part{
        display: flex;
    }

    img{
        width: 130px;
        margin-left: 80px;
        margin-top: 120px;
    }
</style>