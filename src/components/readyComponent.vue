<template>
    <div class="main container-fluid">
        <div class="col-md-12">
            <div class="row justify-content-center">
                <div class="col-md-6">
                    <p>
                    <h1 class="text-center">Ready to grow your business?</h1>
                    <h1 class="text-center">Start with Apex, become faster every second
                    </h1>
                    </p>
                    <p class="row justify-content-center"><button class="btn btn-warning text-white text-center">Start
                            Chatting Now</button></p>

                </div>
            </div>
        </div>
        <div class="row justify-content-center bottom-H">
            <div class="col-md-4 disp">
                <img src="../assets/img/apex2.PNG" alt="">
            </div>
            <div class="col-md-4 disp">
                <img src="../assets/img/list2.PNG" alt="">
            </div>
            <div class="col-md-4 disp">
                <img src="../assets/img/social.PNG" alt="">
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
.main {
    background-color: #f8f8fa;
    padding-block: 40px;
}

.disp {
    display: flex;
    justify-content: center;
}

.bottom-H {
    margin-top: 80px;
}

@media (max-width: 991px) {

    .main {
        padding: 50px;
    }

    .bottom-H {
        margin-top: 10px;
    }
}

.btn-warning {
    background-color: #fb8e0b;
    border: none;
    width: 200px;
    padding: 10px;
}
</style>