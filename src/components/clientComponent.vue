<template>
    <div class="main">
        <div class="col-md-12">
            <div class="row justify-content-center my-3 mb-5">
                <div class="col-md-4">
                    <h1 class="text-center text-white">Our blessed client said about us</h1>
                </div>
            </div>
            <div class="row justify-content-center gy-3">
                <div class="col-md-5">
                    <img src="../assets/img/client1.png" alt="">
                </div>
                <div class="col-md-5">
                    <img src="../assets/img/client2.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
.main {
    background-color: #fb8e0b;
    padding-block: 100px;
    margin-block: 40px;
}

/* img {
    width: 500px;
} */

@media (max-width: 991px) {
    img {
        width: 100%;
    }

    .main {
        padding: 50px;
    }
}
</style>