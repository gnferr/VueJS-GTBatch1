<template>
    <nav class="navbar navbar-light bg-light">
        <a class="navbar-brand ms-5" href="#">
            <img src="../assets/logo.png" class="d-inline-block align-top" alt="">
        </a>
        <div class="nav1 d-flex">
            <a href="" class="nav-link text-dark">Showcase</a>
            <a href="" class="nav-link text-dark">Catalog</a>
            <a href="" class="nav-link text-dark">Delivery</a>
            <a href="" class="nav-link text-dark">Rewards</a>
            <a href=""><img src="../assets/cart-icon.png"><span class="badge badge-danger">2</span></a>
        </div>
    </nav>
</template>
<script>
export default {
    name: 'NavbarComponent',
    props: {
        msg: String
    }
}
</script>
<style scoped>
.nav1 a {
    margin-right: 20px;
}
</style>