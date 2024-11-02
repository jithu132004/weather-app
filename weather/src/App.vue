<template>
  <div id="app">
  <div>
    <main>
      <div class="search-box">
        <input name="" id="" type="text" class="search-bar">
      </div>
      <div class="weather-wrap" >
       <div class="location-box">
          <div class="location">kerala,india</div>
          <div class="date">12 may 2008</div>
       </div>
       <div class="weather-box">
        <div class="temp">20°c</div>
        <div class="weather image">
      </div>
      <div class="weather">cloudy</div>
      <div class="weather-description">brocken cloud</div>
       </div>
      </div>
    </main>
  </div> 
  </div>
</template>



<script>

export default {
  name: 'App',
  data() {
    return{

    }

  }
 
  }

</script>

<style>


     * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;

     }
      body {
        font-family: 'montserrat', sans-serif;
      }

      #app {
        background-image: url("C:\Users\jithu\OneDrive\Desktop\first-weather\weather\src\assets\cold images.png");
        background-size: cover;
        background-position: bottom;
        transition: 0.4s;
      

      }
        
     main {
      min-height: 100vh;
      padding: 25px;
      background-image: linear-gradient(to bottom,rgba(0, 0, 0, 0.25), rgba(0, 0, 0, 0.75));
     }
     .search-box {
      width: 100%;
      margin-bottom: 30px;
     }
    

     .search-box .search-bar {
      display: block;
      width: 100%;
      padding: 15px;
      color: #313131;
      font-size: 20px;
      box-shadow: 0px 0px 16px rgba(0, 0, 0, 0.25);

      appearance: none;
      border: none;
      background: none;
      outline: none;

      background-color: rgba(225, 225, 225, 0.5);
      border-radius: 10px 10px 10px 10px;
      transition: 0.4s;


     }

     .search-box .search-bar:focus {

      background-color: rgba(225, 225, 225, 0.75);
       box-shadow: 0px 0px 16px rgba(0, 0, 0, 0.25) ;
      border-radius: 6px 0px 16px 0px;
     }

     .location-box .location {
       color:#ffffff;
       font-size: 32px;
       font-weight: 500;
       text-align: center;
       text-shadow: 1px 3px rgba(0,  0, 0, 0.25);
     }
     .location-box .date {
      color:#ffffff;
      font-size: 20px;
      font-weight: 300;
      font-style: italic;
      text-align: center;
     }


     .weather-box .temp { 
       text-align: center;
     }

     .weather-box .temp{
      display: inline-block;
      padding: 10px 25px;
      color: #ffffff;
      font-size: 102px; 
      font-weight: 900;

      text-shadow: 3px 6px rgba(0,  0, 0, 0.25);
      background-color: rgba(225,  225, 225, 0.25);
      border-radius: 16px;
      margin:  30px 0px;


       box-shadow: 3px 6px rgba(0,  0, 0, 0.25) ;

     }

     .weather-box .weather {
        color: #ffffff;
        font-size: 35px;
        font-weight: 300;
        font-style: italic;
        text-shadow: 3px 6px rgba(0,  0, 0, 0.25);

     }

     .weather-box .weather-description {
      color: #ffffff;
      font-size: 10px;
      font-weight: 300;
      font-style: italic;

     }
      .weather-box .weather-image {
        position: center;
        
      }


</style>
