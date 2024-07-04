
<template>
  <section class="header_wrap">
    <header class="header">
      <a href="#">
        <img class="logo" src="C:\Users\User\Desktop\Матвей\проект машины\car_project\img\logo.png">
      </a>
      <nav>
        <ul class="menu">
          <li><a href="components\header.vue">Услуги</a></li>
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


  <div class = "uslugi">
    <h1>УСЛУГИ</h1>
  </div>
    <div class="uslugi_photo">
      <div class="usliga1">
      <img class="photo2" src="C:\Users\User\Desktop\Матвей\проект машины\car_project\img\uslugi1.jpg">
      <p style="margin-left: 225px; margin-top: 50px;">Парковка на короткий период</p>
      <p style="margin-left: 225px; margin-top: 25px;"><b>От 500 руб/сутки</b></p>
      </div>
      <div class="usluga2">
      <img class="photo3" src="C:\Users\User\Desktop\Матвей\проект машины\car_project\img\uslugi2.jpg">
      <p style="margin-top: 50px; ">Парковка на длинный период</p>
      <p style="margin-top: 25px;"><b>От 200 руб/сутки</b></p>
      </div>
      <div class="usluga3">
      <img class="photo4" src="C:\Users\User\Desktop\Матвей\проект машины\car_project\img\uslugi3.jpg">
      <p style="margin-top: 50px;">Парковка для электрокаров</p>
      <p style="margin-top: 25px;"><b>От 600 руб/сутки</b></p>
      </div>
    </div>
    <button class="reserved2">Забронировать парковочное место</button>

<div class="how_go">
  <div class="shema">
  <h1>СХЕМА ПРОЕЗДА</h1>
</div>
  <div class="map">
  <center>
  <iframe src="https://yandex.ru/map-widget/v1/?um=constructor%3Ae8410418151905203629ffd0a420e7d64b757538a9049b3b6a6621978a49a6d6&amp;source=constructor" width="900" height="630" frameborder="0" ></iframe>
  </center>
  </div>
  <div class="we">
  <center>
  <h2>Мы на картах</h2>
  <img class="maps_logo1" src="C:\Users\User\Desktop\Матвей\проект машины\car_project\img\maps.png">
  <img class="maps_logo1" src="C:\Users\User\Desktop\Матвей\проект машины\car_project\img\maps2.png">
  </center>
  </div>
  </div>

  <div class="feedback">
    <h1>ОТЗЫВЫ</h1>

    <div class="comment_box">
    <div class="user_info">
    <img class="user_photo" src="C:\Users\User\Desktop\Матвей\проект машины\car_project\img\user.png">
    <h2 class="user_name">user1</h2>
    <h3 class="comment_time">Вчера 17:02</h3>
    </div>
    <p class="comment_text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Expedita sint cumque nam cum distinctio maiores amet incidunt commodi perspiciatis natus similique, est, quibusdam ipsam repellendus quod dolores ad, aspernatur atque.</p>
  </div>

  <div class="comment_box">
    <div class="user_info">
    <img class="user_photo" src="C:\Users\User\Desktop\Матвей\проект машины\car_project\img\user.png">
    <h2 class="user_name">user1</h2>
    <h3 class="comment_time">Вчера 17:02</h3>
    </div>
    <p class="comment_text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Expedita sint cumque nam cum distinctio maiores amet incidunt commodi perspiciatis natus similique, est, quibusdam ipsam repellendus quod dolores ad, aspernatur atque.</p>
  </div>

  <div class="comment_box">
    <div class="user_info">
    <img class="user_photo" src="C:\Users\User\Desktop\Матвей\проект машины\car_project\img\user.png">
    <h2 class="user_name">user1</h2>
    <h3 class="comment_time">Вчера 17:02</h3>
    </div>
    <p class="comment_text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Expedita sint cumque nam cum distinctio maiores amet incidunt commodi perspiciatis natus similique, est, quibusdam ipsam repellendus quod dolores ad, aspernatur atque.</p>
  </div>


  <button class="reserved2">Забронировать парковочное место</button>

</div>



</template>

<style scoped>

.how_go{
  background-color: gray;
}

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

nav a:hover{
  color:#B92727
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
.reserved:hover{
  background-color: #8f1f1f;
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

  .uslugi_photo{
    display:flex;
    gap: 265px;
    margin-top: 50px;
  }

  .photo2{
    border-radius: 10px;
    height: 313px;
    height: 313px;
    margin-left: 225px;
  }

  .photo3{
    border-radius: 10px;
    height: 313px;
    height: 313px;
  }

  .photo4{
    border-radius: 10px;
    height: 313px;
    height: 313px;
  }
  
  .uslugi{
    margin-top: 212px;
    margin-left: 225px;
  }

  .uslugi_name{
    display:flex;
    gap: 265px;
    margin-top: 50px;
    font-size: medium;
  }

  .parkovka1{
    font-size: large;
  }

  .reserved2{
  padding: 10px 20px;
  text-transform:uppercase;
  background-color: #B92727;
  color: white;
  border: none;
  cursor: pointer;
  font-size: 16px;
  border-radius: 20px;
  margin-left: 225px;
  margin-top: 112px;
  margin-bottom: 100px;
}
.reserved2:hover{
  background-color: #8f1f1f;
}

.how_go{
  position: relative;
}

.shema{
  margin-left: 225px;
  padding: 70px;
}

.map{
  margin-bottom: 30px;
}

.maps_logo1{
  height: 100px;
  width: 100px;
  padding: 20px;
  background-color: rgb(206, 206, 206);
  margin-bottom: 20px;
}

.feedback h1{
  margin-top: 200px;
  margin-left: 225px;
}

.user_photo{
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background-color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 10px;
  font-size: 18px;

}
.user_name{
  font-weight: bold;
}

.comment_time{
  margin-left: 5px;
  font-size: 14px;
  line-height: 1.6;
}

.comment_box{
  margin-left: 225px;
  padding: 20px;
  margin-top: 50px;

}

.user_info{
  display: flex;
  align-items: center;
  margin-bottom: 15px;
}


  </style>
