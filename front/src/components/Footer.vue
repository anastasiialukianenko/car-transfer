<script setup>

</script>

<template>
   <section class="bg-sky-200 section" id="footer">
    <p class="text-sky-800">Hаші контакти:</p>
    <a href="tel:+380933485610" class="link rounded-lg bg-sky-400 px-8 py-4 text-xl font-semibold text-white shadow-sm lime:bg-sky-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 sky-visible:outline-sky-600">+380 (93) 503 63 53</a>

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
   </section>
</template>

<style scoped>
.section{
  border-top-right-radius: 20px;
  border-top-left-radius: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
  height: 360px;
}
p{
  text-align: center;
  text-transform: uppercase;
margin-top: 82px;
font-size: 26px;
font-weight: 600;
margin-bottom: 20px
}
.social-icons{
  width: 100%;
    margin-top: 32px;
    justify-content: space-evenly;
    display: flex;
}
@media screen and (min-width: 1024px) {
  .social-icons{
    justify-content: center;
    gap: 28px;
  }
}

</style>
