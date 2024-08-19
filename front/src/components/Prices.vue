<script setup>

</script>

<template>
    <section id="prices">
<h2>Вартість перегону авто</h2>
<p class="desc text-gray-500">Найчастіше наші клієнти замовляють перегон авто з України:</p>

<div>
    <p class="text-gray-500">до Польщі</p>
    <p class="text-sky-800 font-bold">від €200</p>
</div>
<div>
    <p class="text-gray-500">до Німеччини</p>
    <p class="text-sky-800 font-bold">від €500</p>
</div>
<div>
    <p class="text-gray-500">до Франції</p>
    <p class="text-sky-800 font-bold">від €200</p>
</div>
<div>
    <p class="text-gray-500">до Литви</p>
    <p class="text-sky-800 font-bold">від €200</p>
</div>
<div>
    <p class="text-gray-500">до Латвії</p>
    <p class="text-sky-800 font-bold">від €200</p>
</div>
<div>
    <p class="text-gray-500">до Словаччини</p>
    <p class="text-sky-800 font-bold">від €200</p>
</div>
<div>
    <p class="text-gray-500">до Угорщини</p>
    <p class="text-sky-800 font-bold">від €200</p>
</div>
<div>
    <p class="text-gray-500">до Румунії</p>
    <p class="text-sky-800 font-bold">від €200</p>
</div>
<div>
    <p class="text-gray-500">до Італії</p>
    <p class="text-sky-800 font-bold">від €200</p>
</div>
<div>
    <p class="text-gray-500">до Іспанії</p>
    <p class="text-sky-800 font-bold">від €200</p>
</div>
<div>
    <p class="text-gray-500">до Іспанії</p>
    <p class="text-sky-800 font-bold">від €200</p>
</div>
<div>
    <p class="text-gray-500">до Австрії</p>
    <p class="text-sky-800 font-bold">від €200</p>
</div>

<a href="tel:+380933485610" class="link rounded-lg bg-sky-900 px-12 py-4 text-xl font-semibold text-white shadow-sm lime:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 sky-visible:outline-sky-600">Дізнатись ціну</a>

</section>
</template>

<style scoped>
section{
    margin-bottom: 68px;
}
h2{
    font-size: 42px;
    font-weight: 600;
    margin-bottom: 32px;
    text-align: center;
}
.desc{
    font-size: 22px;
    text-decoration: underline;
    text-decoration-color: skyblue;
    font-weight: 500;
    margin-bottom: 28px;
}
div{
    display: flex;
    justify-content: space-between;
    margin-bottom: 22px;
}
p{
    font-size: 18px;
}

.link{
    display: flex;
    justify-content: center;
    width: 280px;
    margin: 38px auto 0 ;
}

@media screen and (min-width: 1024px) {
    div{
        max-width: 50%;
        margin: 22px auto;
    }
    .desc{
        text-align: center;
        font-size: 28px;
    }
}
</style>
