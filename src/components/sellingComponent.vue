<template>
    <div class="main container-fluid">
        <div class="col-md-12">
            <div class="row justify-content-center gy-3">
                <div class="col-12 col-lg-4 order-2 order-lg-1">
                    <p>
                    <h2>Start selling directly inside conversations</h2>
                    </p>
                    <p>There are many variations of passage of Lorem available, but the majority have sufferes all
                        injected humour or randomised words which dont look even sighlty baleivable. </p>
                    <p><button class="btn btn-warning text-white">Start Chatting Now</button></p>

                </div>
                <div class="col-md-4 order-1 order-lg-2">
                    <img src="../assets/img/selling.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
.main {
    padding-block: 100px;
}

img {
    width: 500px;
}

@media (max-width: 991px) {
    img {
        width: 100%;
    }

    .main {
        padding: 50px;
    }
}

.btn-warning {
    background-color: #fb8e0b;
    border: none;
}
</style>