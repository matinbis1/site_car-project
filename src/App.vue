
<template>
  <section class="header_wrap">
    <header class="header">
      <a href="#">
        <img class="logo" src="C:\Users\User\Desktop\Матвей\проект машины\car_project\img\logo.png">
      </a>
      <nav>
        <ul class="menu">
          <li><a href="#">Услуги</a></li>
          <li><a href="#">Схема проезда</a></li>
          <li><a href="#">Отзывы</a></li>
          <li><a href="#">Контакты</a></li>
        </ul>
      </nav>
      <div class="contact-info">
        <span>+7 900 000 00 00</span>
        <span>Магнитогорск, Ленина 1</span>
      </div> 
      <button class="reserved">Забронировать</button>
    </header>
  </section>
  <div class = "car_photo">
    <img class="photo1" src="C:\Users\User\Desktop\Матвей\проект машины\car_project\img\car_photo.jpg">
  </div>
  <div class="wonder">
    <h1>Wonder Parking - для тех, кто ценит свои вложения: безопасное и удобное хранение вашего автомобиля</h1>
  </div>
</template>

<style scoped>

.header{
  position: fixed;
  top: 0;
  background-color: white;
  width: 100%;
  z-index: 1000;
  display: flex;
  justify-content: space-between;
  align-items: center;
  color:black;
  padding: 28px;
  box-sizing: border-box;
}
.menu{
  display: flex;
  list-style: none;
  gap: 48px;
  text-transform:uppercase;
  font-style: medium;
}
nav a{
  color: black;
  text-decoration: none;
}
.logo{
height: 60px;
width: 60px;
}
.contact-info{
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: 16px;
  border-radius: 3px;
}
.reserved{
  padding: 10px 20px;
  text-transform:uppercase;
  background-color: #B92727;
  color: white;
  border: none;
  cursor: pointer;
  font-size: 16px;
  border-radius: 20px;
}
.photo1{
  width: 100%;
  height: 100%;
  position: relative;
  top:0;
  left:0;
}

.wonder {
  text-transform:uppercase;
  position: absolute;
  color: rgb(255, 255, 255);
  left: 50%;
  top: 50%;
  transform: translate(-70%, 300%);
  background-color: rgba(41, 41, 41, 0.8);
  padding: 10px;
  font-size: 14px;
  }
</style>
