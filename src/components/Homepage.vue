<template>
  <div id="main" class="container-fluid m-0 p-0">
    <div id="home-page" class="bg-danger p-4">
      <div id="right-side">
        <h1>NFTerra</h1>
        <p>An NFT-based game that connects digital art<br>with real places and allows players to explore it.</p>
        <button>lightpaper</button>
        <div>
          <button>discord</button>
          <button>telegram</button>
        </div>
      </div>
      <div id="left-side">
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
  #left-side {
    height: 100vh;
  }
  #main {
    margin: auto;
  }

  img {
    max-width: 100%;
    max-height: 100%;
  }

  #right-side {
      float: left;
  width: 50%;
    
  }

  #footer {
  }

  #home-page {
    display: flex;
    justify-content: center;
      align-items: center;

  }

</style>
