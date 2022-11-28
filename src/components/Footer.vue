<template>
    <div>
        <div class="d-flex justify-content-center">
            <img src="../assets/logo.png" alt="Logo.png" style="margin-top: 30px;">
        </div>
        <div class="footer d-flex flex-row justify-content-around m-5">
            <div class="d-flex flex-column">
                <p class="font-weight-bold">Overview</p>
                <a href="">Shipping</a>
                <a href="">Refund</a>
                <a href="">Promotion</a>
            </div>
            <div class="d-flex flex-column">
                <p class="font-weight-bold">Company</p>
                <a href="">About</a>
                <a href="">Carrer</a>
                <a href="">Contact Us</a>
            </div>
            <div class="d-flex flex-column">
                <p class="font-weight-bold">Explore</p>
                <a href="">Terms & Conds</a>
                <a href="">Privacy Policy</a>
                <a href="">For Developer</a>
            </div>
            <div class="d-flex flex-column">
                <p class="font-weight-bold">Special Letter</p>
                <div class="input-group mb-3">
                    <input type="text" class="form-control" placeholder="Input email" aria-label="Recipient's username"
                        aria-describedby="basic-addon2">
                    <span class="input-group-text" id="basic-addon2"><img src="../assets/tele-icon.png"></span>
                </div>

            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'FooterComponent',
    props: {
        msg: String
    }
}
</script>
<style scoped>
a {
    text-decoration: none;
    color: rgb(34, 34, 34);
}

span {
    background-color: pink;
}
</style>