<template>
    <div class="container-fluid">
        <div class="utama m-5">
            <div class="kgambar">
                <img src="../assets/side-1.png">
                <img src="../assets/side-2.png">
                <img src="../assets/side-3.png">
                <img src="../assets/side-1.png">
                <img src="../assets/side-2.png">
            </div>
            <div class="tgambar">
                <img src="../assets/chair.png" id="tgambare" style="border-radius: 25px;width: 500px;">
            </div>
            <div class="text">
                <h2 id="namaKursi">Chair Thatty</h2>
                <p id="hargaKursi">IDR 15.000.000</p>
                <a class="btn text-dark rounded" type="button" id="buttonShipping" style="text-decoration: none;"
                    href="#"><img src="../assets/cart-icon.png" style="margin-right:10px" width="20px">Add
                    to
                    Cart</a>
                <p style="font-weight: bold;" class="mt-5">About the product :</p>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Atque eum, aperiam, dolores, nemo esse
                    aut
                    ipsum expedita nulla accusantium magnam corrupti facere debitis sed quam dicta labore non
                    obcaecati
                    inventore!</p>

            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'GalleyComponent',
    props: {
        msg: String
    }
}
</script>
<style scoped>
.utama {
    display: flex;
}

.btn {
    background-color: pink;
}

.utama .kgambar {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 90px;
}

.utama .kgambar img {
    border: 1px solid pink;
    border-radius: 25%;
}
</style>