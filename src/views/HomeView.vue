<template>
  <div class="home">
    <div class = "header1">
      <h1 style="color: #f8c11a; font-size: 36px; margin: 0; ">
        Интеграция внешних платформ в цифровой МИЭМ
      </h1>
      <h3 style="font-size: 18px; margin: 25px 0 27px 0; ">Единый онлайн-сервис для дистанционного обучения</h3>
      <a href="https://online.miem.hse.ru/#/"><button  class="button">Перейти</button></a>
    </div>    
      <div class="video1">
        <iframe width="720" height="405" src="https://www.youtube.com/embed/crWkIPL36I8"
        title="YouTube video player" frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media;
        gyroscope; picture-in-picture" allowfullscreen></iframe>
      </div>
      <div class="header2">
        <h1 style="font-size: 42px;">5 видеоплатформ для проведения занятий</h1>
        <div>
          <img src="../images/labels.png" alt="" style="width: 23%; margin: 48px;" >
        </div>

        <div class = "wrap">
          <div class = "icon1">
            <img class = "icon" src="../images/p.png" alt="">
            <p>автоматическое подключение</p> <p>к текущему собранию</p>
          </div>
          <div class = "icon1">
            <img class = "icon" src="../images/clock.png" alt="">
            <p>Zoom-конференции</p> <p>без временных ограничений</p>
          </div>
        </div>
        <div class = "wrap1">
          <div class = "icon1">
            <img class = "icon" src="../images/calendar.png"  alt="">
            <p>многофункциональный</p> <p>календарь с расписанием</p> <p>занятий и встреч</p>
          </div>
          <div class = "icon1">
            <img class = "icon" src="../images/ozh.png" alt="">
            <p>запись дитсанционных</p> <p>и очных пар</p>
          </div>
          <div class = "icon1">
            <img class = "icon" src="../images/peolple.png" alt="">
            <p>статистика</p> <p>посещаемости</p> <p>онлайн-занятий</p>
          </div>
        </div>
      </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:ital,wght@0,600;1,400&display=swap');
.header1{
  margin: 120px;
  text-align: center;
  font-family: 'Source Sans Pro', sans-serif;
}
.header2{
  text-align: center;
  font-family: 'Source Sans Pro', sans-serif;
  margin-bottom: 100px;
}
.button{
  display: inline-block;
  font-family: 'Source Sans Pro', sans-serif;
  line-height: 1.5;
  color: #212529;
  text-align: center;
  text-decoration: none;
  vertical-align: middle;
  cursor: pointer;
  -webkit-user-select: none;
  -moz-user-select: none;
  user-select: none;
  background-color: transparent;
  border: 1px solid transparent;
  padding: 0.7rem 1.7rem;
  font-size: 18.75px;
  border-radius: 1.5rem;
  transition: color .15s;
  border-color: black;
  border:1px solid black; 
}
.video1 {
  text-align: center;
  margin-bottom: 120px;
}
.icon {
  padding: 0 100px;
  max-width: 43%;
}
.wrap {
         width: 800px;/*фиксируем ширину обертки*/
         margin: 0 auto;/*центрируем ее*/
         /* background: darkgray; */
         height: 210px; 
         margin-bottom: 25px;
        }
.wrap1 {
         width: 1250px;/*фиксируем ширину обертки*/
         margin: 0 auto;/*центрируем ее*/
         /* background: darkgray; */
         height: 250px; 
        }        
 
.icon1 {
        float: left; /*Задаем обтекание*/
        font-size: 20px;
        /* background: dodgerblue; */
        
        width: 350px; /*Фиксируем ширину блока*/
        margin-right: 100px;
        text-align: center; /*Центрируем текст по горизонтали*/
}
.wrap :last-child {
        margin-right: 0px;/*Убираем поле последнего div-а*/
}
.wrap1 :last-child {
        margin-right: 0px;/*Убираем поле последнего div-а*/
}
.wrap p {
  margin: 0;
  font-size: 25px;
  
}
.wrap1 p {
  margin: 0;
  font-size: 25px;
}
</style>