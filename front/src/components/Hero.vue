<script setup>

</script>

<template>
    <section class="hero">
        <div class="social-icons">
        <a href="viber://chat?number=+1234567890" target="_blank" aria-label="Chat on Viber">
        <img src="../assets/viber.svg" alt="Viber Icon" style="width: 42px; height: 42px;">
        </a>
        <a href="telegram://chat?number=+1234567890" target="_blank" aria-label="Chat on Telegram">
        <img src="../assets/telegram.svg" alt="Telegram Icon" style="width: 42px; height: 42px;">
        </a>
        <a href="whatsup://chat?number=+1234567890" target="_blank" aria-label="Chat on Whatsapp">
        <img src="../assets/whatsapp.svg" alt="Whatsapp Icon" style="width: 42px; height: 42px;">
        </a>
        </div>

        <h1>Перегін вашого авто до Європи</h1>
        <p>Швидко, ефективно та надійно перевеземо ваше авто з <span class="text-sky-800 font-bold">України в Європу</span>, або з <span class="text-sky-800 font-bold">Європи до України</span></p>
        <a href="tel:+380933485610" class="rounded-lg bg-sky-400 px-12 py-4 text-xl font-semibold text-white shadow-sm lime:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 sky-visible:outline-sky-600">Замовити</a>


        <div class="back-image">
        </div>

        <!-- //viber telegram -->
    </section>
</template>

<style scoped>
.hero{
    position: relative;
    height: 700px;
    background-color: #e2e3e6b4;
    border-radius: 20px;
    padding: 15px;
    margin-bottom: 68px;
}
h1{
    margin-top: 46px;
    color: rgb(10, 24, 51);
    font-size: 42px;
    line-height: 1.1;
    font-weight: 600;
}
p{
    font-size: 20px;
    line-height: 1.4;
    font-weight: 400;
    margin-top: 32px;
    margin-bottom: 48px;
    width: 90%;
}

.back-image {
    position: absolute;
    width: 90%;
    right: 0;
    bottom: -80px;
    height: 50%;
    background-image: url(../assets/car.png);
    background-size: cover;
    background-repeat: no-repeat;
}

.social-icons{
    margin-top: 32px;
    justify-content: space-evenly;
    display: flex;
}
</style>
