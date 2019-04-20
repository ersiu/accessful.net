<template>
    <div>
        <div class="card text-white">
            <img class="card-img" src="../assets/dashboard.jpg" alt="">
            <div class="card-img-overlay">
                <h4 class="card-title">Data analytics</h4>
                <p class="card-text">Business and management dashboard for better decision and insights</p>
                <p class="card-text">
                    <small class="text-muted">Last updated 3 mins ago</small>
                </p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'featureSection',
        props: {
            msg: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .card {
        text-shadow: 1px 1px 1px #000;
    }
</style>
