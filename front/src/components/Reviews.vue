<script setup>

</script>

<template>
    <section id="review">
        <h2>Чому нам довіряють?</h2>
        <ul>
            <li>
                <img src="../assets/IMG_1582.jpeg" alt="car">
                <div class="group">
                    <p class="type">Перегін авто своїм ходом</p>
                    <p class="city">Львів - Штутгарт</p>
                    <div class="wrap">
                        <p class="price">
                          €600
                        </p>
                        <p class="time">
                            1100 км — від 17 год
                        </p>
                    </div>
                </div>
            </li>
            <li>
                <img src="../assets/IMG_1582.jpeg" alt="car">
                <div class="group">
                    <p class="type">Перегін авто своїм ходом</p>
                    <p class="city">Львів - Штутгарт</p>
                    <div class="wrap">
                        <p class="price">
                          €600
                        </p>
                        <p class="time">
                            1100 км — від 17 год
                        </p>
                    </div>
                </div>
            </li>
            <li>
                <img src="../assets/IMG_1582.jpeg" alt="car">
                <div class="group">
                    <p class="type">Перегін авто на лафеті</p>
                    <p class="city">Львів - Штутгарт</p>
                    <div class="wrap">
                        <p class="price">
                          €600
                        </p>
                        <p class="time">
                            1100 км — від 17 год
                        </p>
                    </div>
                </div>
            </li>
            <li>
                <img src="../assets/IMG_1582.jpeg" alt="car">
                <div class="group">
                    <p class="type">Перегін авто своїм ходом</p>
                    <p class="city">Львів - Штутгарт</p>
                    <div class="wrap">
                        <p class="price">
                          €600
                        </p>
                        <p class="time">
                            1100 км — від 17 год
                        </p>
                    </div>
                </div>
            </li>
        </ul>
    
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
}
ul{
    display: flex;
    flex-direction: column;
    gap: 28px;
    align-items: center;
    justify-content: center;
}
@media screen and (min-width: 768px) {
   ul{
    flex-direction: row;
    flex-wrap: wrap;
  }
}
@media screen and (min-width: 1440px) {
   ul{
    justify-content: space-around;
    gap: 0;
  }
}
li{
    display: flex;
    flex-direction: column;
    width: 280px;
    height: 520px;
    border-radius: 20px;
    border: 1px solid #e2e3e6b4;;
    justify-content: space-between;
}
img{
    background-color: bisque;
    border-top-right-radius: 20px;
    border-top-left-radius: 20px;
}
.group{
    padding: 15px 0 0;
    display: flex;
    flex-direction: column;
}
.type{
    font-weight: 500;
    padding-left: 15px;
    margin-bottom: 8px;
}
.city{
    padding-left: 15px;
margin-bottom: 20px;
font-weight: 700;
font-size: 20px;
}
.wrap {
    display: flex;
    border-top: 1px solid #e2e3e6b4;
    justify-content: space-evenly;
}
.price{
border-right: 1px solid #e2e3e6b4;
padding: 15px 15px;
color: rgb(7 89 133);
font-weight: 600;
font-size: 18px;
}
.time{
    padding: 15px 15px;
    color: grey;
font-weight: 600;
font-size: 16px;
}
</style>
