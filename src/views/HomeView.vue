<script setup>
import HeaderComponent from '../components/HeaderComponent.vue'
</script>
<template>
<section id="home">
    <div class="manuel">
    </div>
    <div class="photo">
        <div class="photo_sous">
        </div>
    </div>
    <div class="paysage">
        <div class="paysage_sous"></div>
    </div>
    <div class="logiciel">
        <div class="logiciel_sous"></div>
    </div>
    <div class="qrcode">
        <div class="qrcode_sous">
        </div>
    </div>
</section>
</template>
<style>
*{
    margin: 0;
    padding: 0;
}

section {
    width: 100%;
}
.manuel {
    width: 100%;
    height: 600px;
    background-image: url('../../public/images/manuel.jpeg');
    background-size: cover;
}

.photo {
    width: 100%;
    height: 600px;
    background-image: url('../../public/images/photo.jpeg');
    background-size: cover;
}

.photo_sous {
    width: 600px;
    height: 600px;
    background-color: #FFD400;
    border-top-right-radius: 50%;
    border-bottom-right-radius: 50%;
}

.paysage {
    width: 100%;
    height: 600px;
    background-image: url('../../public/images/paysage.jpeg');
    background-size: cover;
}

.paysage_sous {
    width: 600px;
    height: 600px;
    background-color: #00CC00;
    float: right;
    border-top-left-radius: 50%;
    border-bottom-left-radius: 50%;
}

.logiciel {
    width: 100%;
    height: 600px;
    background-image: url('../../public/images/3D.jpeg');
}

.logiciel_sous {
    width: 600px;
    height: 600px;
    background-color: #0099FF;
    border-top-right-radius: 50%;
    border-bottom-right-radius: 50%;
}

.qrcode {
    width: 100%;
    height: 600px;
    background-image: url('../../public/images/qrcode.jpeg');
    background-size: cover;
}

.qrcode_sous {
    width: 600px;
    height: 600px;
    background-color: #CC0000;
    float: right;
    border-top-left-radius: 50%;
    border-bottom-left-radius: 50%;
}

</style>
