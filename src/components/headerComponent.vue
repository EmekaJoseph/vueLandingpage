<template>
    <div>
        <nav class="py-3 navbar navbar-expand-lg navbar-light bg-white">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">Apex</a>
                <div style="margin-left: 200px;" class="collapse navbar-collapse" id="navbarNavAltMarkup">
                    <div class="navbar-nav">
                        <span class="nav-link mx-3"><a href="#">Demos</a></span>
                        <span class="nav-link mx-3"><a href="#">About</a></span>
                        <span class="nav-link mx-3"><a href="#">Blog</a></span>
                        <span class="nav-link mx-3"><a href="#">Pages</a></span>
                        <span class="nav-link mx-3"><a href="#">Contact</a></span>
                    </div>

                </div>
                <div class="d-none d-xl-block d-flex me-4">
                    <span class="me-5"><button class="btn btn-link text-dark text-decoration-none">Login
                        </button></span>
                    <span><button class="btn btn-warning text-white">Get Started Free</button></span>
                </div>
                <span class="navbar-toggler border-0">
                    <span class="navbar-toggler-icon"></span>
                </span>
            </div>
        </nav>
    </div>
</template>

<script setup>

</script>

<style scoped>
.nav-link a {
    color: #111;
    cursor: pointer;
    text-decoration: none;
}

.navbar-brand {
    margin-left: 150px
}

@media (max-width: 991px) {
    .navbar-brand {
        margin-left: 10px
    }
}
</style>