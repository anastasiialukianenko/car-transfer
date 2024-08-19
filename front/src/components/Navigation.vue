<script setup>

</script>

<template>
    <nav class="navigation">
      <ul>
        <li><a href="#steps">Кроки</a></li>
        <li><a href="#conditions">Умови</a></li>
        <li><a href="#review">Відгуки</a></li>
        <li><a href="#prices">Ціни</a></li>
        <li><a href="#footer">Контакти</a></li>
      </ul>
    </nav>
  </template>

<style scoped>
nav{
    width: 100%;
    padding: 0 0 28px;
}
ul{
    display: flex;
    gap: 60px;
    justify-content: flex-start;
}
li{
  font-weight: 600;
  cursor: pointer;
}
li:hover{
  color: rgb(7 89 133)
}
</style>
