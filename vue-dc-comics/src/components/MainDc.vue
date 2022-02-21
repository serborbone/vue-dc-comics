<template>
  <section id="main">

      <!-- MAIN TOP - BLACK BAR -->
      <div class="wrap-black">
          <div class="container">
              <div class="main-top">

                  <h2>Content goes here</h2>

              </div>
          </div>
      </div>

      <!-- MAIN BOTTOM - BLUE BAR -->
    <div class="wrap-blue">
        <div class="container">
            <div class="main-bottom">
            </div>
        </div>
    </div>

  </section>
</template>

<script>
</script>

<style scoped>
    
     .container {
      height: 100%;
    }

     .wrap-black {
      height: 150px;
      background-color: #1C1C1C;
    }

    .main-top {
      height: 100%;
      display: flex;
      align-items: center;
    }

    .main-top h2 {
      color: #fff;
    }

    .wrap-blue {
      background-color: #0282F9;
      height: 170px;
    }

   
</style>