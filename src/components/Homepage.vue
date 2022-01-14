<template>
  <div id="main" class="container-fluid m-0 p-0">
    <div id="home-page" class="bg-danger p-4">
      <div id="left-side">
        <h1>NFTerra</h1>
        <p>An NFT-based game that connects digital art<br>with real places and allows players to explore it.</p>
        <button id="lightpaper">LIGHTPAPER</button>
        <div id="socials">
          <button id="discord" onclick="goToDiscord()"/>
          <button id="telegram"/>
        </div>
      </div>
      <div id="right-side">
        <img id="main-image" src="../assets/main.png">
      </div>
    </div>
    <div id="footer" class="bg-warning p-4">
      footer
    </div>
  </div>
</template>

<script>
export default {
  // name: 'HelloWorld',
  data () {
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
  }

  #home-page {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  #right-side {
    height: 100%;
    padding-top: 5vh;
    padding-left: 20px;
    padding-right: 20px;
  }

  #right-side img {
    max-width: 100%;
    max-height: 95vh;
  }

  #left-side {
    width: 50%;
    align-content: right;
    align-items: right;
  }

  #footer {
    background-color: lightblue;
    height: 70px;
  }

  button {
    border: none;
    color: white;
  }

  #lightpaper {
    background-color: #AD0262;
    padding: 18px 26px;
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
</style>
