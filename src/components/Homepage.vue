<template>
  <div id="main">
    <div id="header"/>
    <div id="home-page">
      <div id="left-side">
        <h1>NFTerra</h1>
        <p>An NFT-based game that connects digital art<br>with real places and allows players to explore it.</p>
        <button id="lightpaper" v-on:click="counter += 1">Lightpaper {{ counter }}</button>
        <button id="getintouch">Contact us</button>

        <div id="socials">
          <button id="discord" onclick="goToDiscord()"/>
          <button id="telegram"/>
        </div>
      </div>
      <div id="right-side">
        <img id="main-image" src="../assets/main.png">
      </div>
    </div>
    <div id="footer">
      © 2021 codeers
    </div>
  </div>
</template>

<script>
export default {

  data () {
    var example1 = new Vue({
      el: '#example-1',
      data: {
       counter: 0
      }
    })
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  h1 {
    font-size: 62px;
  }
  
  p {
    font-size: 20px;
  }

  #main {
    margin: auto;
    height: 100vh;
  }

  #home-page {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 90%;
  }

  #right-side {
    height: 100%;
    padding-left: 20px;
    padding-right: 20px;
  }

  #right-side img {
    max-width: 100%;
    max-height: 100%;
  }

  #left-side {
    width: 50%;
    padding-left: 20px;
    padding-right: 20px;
  }

  #footer {
    background-color: #AD0262;
    height: 5%;
    color: white;
    padding-top: 10px;
  }

   #header {
    height: 5%;
  }

  button {
    border: none;
    color: white;
  }

  #getintouch {
    background-color: #AD0262;
    padding: 18px 26px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 14px;
    font-weight: 600;
    border-radius: 4px;
  }

  #lightpaper {
    color: #AD0262;
    border: 2px solid #AD0262;
    background-color: white;
    padding: 16px 24px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 14px;
    font-weight: 600;
    border-radius: 4px;
  }

  #socials {
    margin-top: 10px;
  }

  #discord {
    background: url(../assets/discord.png) no-repeat;
    width: 50px;
    height: 50px;
    background-size: 100%;
    margin: 10px;
  }

  #telegram {
    background: url(../assets/telegram.png) no-repeat;
    width: 45px;
    height: 45px;
    background-size: 100%;
    margin: 10px;
  }

@media(max-width:768px){
  #main {
    height: 100%;
  }

  #home-page {
    display: inline;
  }
}

</style>
