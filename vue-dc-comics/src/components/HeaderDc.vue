<template>
  <div id="header">
    
    <div class="header">

        <div class="container">

            <!-- LOGO HEADER -->
            <div class="logo-header">
                <img src="../assets/img/dc-logo.png" alt="Logo DC Comics">
            </div>

            <!-- MENU HEADER -->
            <div class="menu-header">
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">Tv</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Collectibles</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">Fans</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
                </ul>
            </div>
            
        </div>
        
    </div>

  </div>
</template>

<script>
</script>

<style scoped>
    .header {
      height: 120px;
    }

    .logo-header {
      height: 80px;
    }

    .logo-header img {
      height: 100%;
    }

    .menu-header {
      height: 100%;
      font-size: 14px;
    }

    .menu-header ul {
      display: flex;
      list-style: none;
      text-transform: uppercase;
      height: 100%;
    }

    .menu-header ul li {
      height: 100%;
      padding: 0 13px 0 13px;
    }

    .menu-header ul li a {
      padding: 0 3px 0 3px;
      text-decoration: none;
      color: #1C1C1C;
      height: 100%;
      display: flex;
      align-items: center;
      box-sizing: border-box;
    }

    .menu-header ul li a:hover {
      color: #0282F9;
      border-bottom: 4px solid #0282F9;
    }

    .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      height: 100%;
    }
</style>