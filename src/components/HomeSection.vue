<template>
    <!-- <div class="fullscreen-bg">
                <video loop muted autoplay poster="../assets/Feeling-the-Air.jpg" class="fullscreen-bg__video">
                        <source src="../assets/Feeling-the-Air.mp4" type="video/mp4">
                    </video>
            </div> -->
    
    <div class="coverBanner text-center">
        <div class="my-flex-container d-flex flex-column p-2 mx-auto">
            <div class="my-flex-item2 p-5">
                <img src="../assets/logo standard@1x.png" alt="">
            </div>
            <br>
            <br>
            <div class="my-flex-item2 p-5 ">
                <h5 class="display-4">Data has a <strong>better idea</strong>
                </h5>
                <p class="lead">We build digital and data solutions that gives you a competitive advantage</p>
            </div>
            <div class="my-flex-item2 p-5">
                <p class="lead">
                    <a href="#" class="btn btn-lg btn-secondary">Learn more</a>
                </p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'HomeSection'
    };
</script>

<style scoped>
    .coverBanner {
        background: url(../assets/cover1.jpg);
        background-attachment: fixed;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        color: #ffffff;
        height: 800px;
        /* text-shadow: -1px -1px 0 hsl(280, 70%, 35%), -2px -2px 1px hsl(280, 70%, 35%); */
        text-shadow: 1px 1px 1px grey;
        text-shadow: 0 .05rem .1rem rgba(0, 0, 0, .5);
        box-shadow: inset 0 0 5rem rgba(0, 0, 0, .5);
        display: -ms-flexbox;
        display: flex;
        flex-wrap: wrap;
    }

    .my-flex-container {
        /* border: 2px solid green;
        margin-bottom: 20px; */
    }

    .my-flex-container-column{
        border: 2px solid green;
        height: 200px;
        margin-bottom: 20px;
    }
    
    .my-flex-item {
        background-color: lightgrey;
        border: 1px dotted grey;
        height: 48px;
    }

    .my-flex-item-2 {
        background-color: lightgrey;
        border: 1px dotted grey;
        height: 130px;
    }
    
    /* .item-hl {
        min-height: 300px;
    } */
    
    
    /* .fullscreen-bg {
        position: fixed;
        top: 0;
        right: 0;
        bottom: 0;
        left: 0;
        overflow: hidden;
        z-index: -100;
    }
    
    .fullscreen-bg__video {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
    
    .cover-container {
        max-width: 42em;
        height: 800px;
        min-height: 600px;
        padding: 0 1.5rem;
    }
    
    .cover .btn-lg {
        padding: .75rem 1.25rem;
        font-weight: 700;
    }
    
    .nav-masthead .nav-link {
                        padding: .25rem 0;
                        font-weight: 700;
                        color: rgba(255, 255, 255, .5);
                        background-color: transparent;
                        border-bottom: .25rem solid transparent;
                    }
                    
                    .masthead-brand {
                        font-family: 'Alba';
                    } */
    
    
    /* .cover {
                        padding: 0 1.5rem;
                    } */
    
    
    /* .mastfoot {
                        color: rgba(255, 255, 255, .5);
                    }
                     */
    
    
    /* Custom default button */
</style>