<template>
    <div id="coverSection" class="text-center">
        <div class="cover-container d-flex w-100 h-100 p-3 mx-auto flex-column">
            <main>
                <div class="row">
                    <div class="col text-center py-5">
                        <img src="../assets/logo standard@1x.png" alt="">
                    </div>
                </div>
                <div class="row">
                    <div class="col text-center py-3">
                        <h5 class="display-4">Data has a <strong>better idea</strong>
                        </h5>
                        <p class="lead">We provide data analytic and digital marketing solutions</p>
                        <p class="lead">
                            <a href="#" class="btn btn-lg btn-secondary">Learn more</a>
                        </p>
                    </div>
                </div>
            </main>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'HomeSection'
    };
</script>

<style scoped>
    #coverSection {
        /* background: url(../assets/img/home6.jpg); */
        background-color: #333;
        background-repeat: no-repeat;
        background-size: cover;
        background-attachment: fixed;
        height: 100%;
        color: #ffffff;
        /* text-shadow: -1px -1px 0 hsl(280, 70%, 35%), -2px -2px 1px hsl(280, 70%, 35%); */
        text-shadow: 1px 1px 1px grey;
        text-shadow: 0 .05rem .1rem rgba(0, 0, 0, .5);
        box-shadow: inset 0 0 5rem rgba(0, 0, 0, .5);
        display: -ms-flexbox;
        display: flex;
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
    }
    
    .cover {
        padding: 0 1.5rem;
    }
    
    .cover-container {
        max-width: 42em;
        height: 100%;
        min-height: 600px;
        padding: 0 1.5rem;
    }
    
    .cover .btn-lg {
        padding: .75rem 1.25rem;
        font-weight: 700;
    }
    
    .mastfoot {
        color: rgba(255, 255, 255, .5);
    }
    
    
    /* Custom default button */
</style>