<template>
    <div>
        <!-- NAVBAR WITH RESPONSIVE TOGGLE -->
        <nav class="navbar navbar-expand-sm navbar-dark bg-dark fixed-top">
            <div class="container">
                <a href="/"><img class="navbar-brand" src="../assets/A_Logo@2x.png" alt="logo" ></a>
                <!-- <a class="navbar-brand" href="#">Accessful</a> -->
                <button class="navbar-toggler" data-toggle="collapse" data-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
              </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item">
                            <a class="nav-link" href="#home-section">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#feature-section">Explore</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
</template>

<script>
    export default {
        name: 'theNavBar'
    }
</script>

<style scoped>
    .navbar {
        /* border-bottom: #d68700 3px solid; 
        opacity: 0.8; */
    }
    
    .navbar-brand {
        height: 50px;
    }

    .nav-link {
        color: rgb(50, 50, 50);
    }
</style>