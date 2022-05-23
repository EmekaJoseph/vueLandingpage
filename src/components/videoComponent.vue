<template>
    <div class="videoComponent">
        <div class="col-md-12">
            <div class="row justify-content-center gy-3">
                <div class="col-md-5">
                    <img src="../assets/img/video.png" alt="">
                </div>
                <div class="col-12 col-lg-4">
                    <p>
                    <h3>Meet your customers with live video chat</h3>
                    </p>
                    <p>Get paychecks up to two days early, Get a $20 bonus when you receive qualifying direct deposits.
                    </p>
                    <p>Get paychecks up to two days early, Get a $20 bonus when you receive qualifying direct deposits.
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
.videoComponent {
    background-color: #faf9f9;
    padding-block: 100px;
    margin-block: 40px;
}

img {
    width: 500px;
}

@media (max-width: 991px) {
    img {
        width: 100%;
    }

    .videoComponent {
        padding: 50px;
    }
}
</style>