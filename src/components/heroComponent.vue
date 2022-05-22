<template>
    <div>
        <div class="largeFront">
            <div class="container">
                <div class="row gy-3">
                    <div class="col-md-6 hero">
                        <p class="fs-1 fw-bold">
                            Start chatting with customers, anytime, anywhere with Apex.
                        </p>
                        <p>
                            Great software that allows you to chat from any <br> place at any time
                            without any interruption.
                        </p>
                        <a style="width: 200px;" href="#" class="btn btn-warning text-white">Book
                            now <i class="bi bi-arrow-right"></i></a>
                        <br>
                        <div class="mt-5 col-md-10">
                            <div class="row g-1">
                                <div class="col-md-8">
                                    <div class="row">
                                        <div class="col-5">
                                            <img src="../assets/img/cusImg.png" alt="">
                                        </div>
                                        <div class="col-6 cusPane">
                                            <h4>2,291</h4>
                                            <span>Happy Customers</span>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-md-4">
                                    <h4>4.8/5</h4>
                                    <span>Happy Customers</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div>
                            <img class="imgHero" src="../assets/img/hold-Phone.png" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
.largeFront {
    min-height: 100vh;
    background-size: cover;
    background-position: center center;
    padding: 15px;
}

.hero {
    margin-top: 100px
}

.cusPane {
    border-right: 2px solid #4e4d4d;
}



@media (max-width: 991px) {
    .hero {
        margin-top: 20px
    }

    .cusPane {
        border: none;
    }

    .imgHero {
        width: 300px;
    }
}
</style>