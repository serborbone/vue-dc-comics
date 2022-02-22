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
                <!-- LISTA LINK -->
                <ul>
                    <li v-for="(link, index) in linksMain" :key="index">
                        <div class="li-img">
                            <img :src="link.img">
                        </div>
                        <a href="#">{{link.title}}</a>
                    </li>
                </ul>
                <!-- FINE LISTA LINK -->
            </div>
        </div>
    </div>

  </section>
</template>

<script>
  export default {
    name: 'MainDc',
    data() {
      return {

          linksMain: [
          
            {
              img: require('../assets/img/buy-comics-digital-comics.png'),
              title: 'Digital Comics',
            },

            {
              img: require('../assets/img/buy-comics-merchandise.png'),
              title: 'Dc Merchandise',
            },
            
            {
              img: require('../assets/img/buy-comics-subscriptions.png'),
              title: 'Subscription',
            },

            {
              img: require('../assets/img/buy-comics-shop-locator.png'),
              title: 'Comic Shop Locator',
            },

            {
              img: require('../assets/img/buy-dc-power-visa.svg'),
              title: 'Dc Power Visa',
            },
          
          ]
          
      }
    },
  }
</script>

<style scoped lang="scss">

     @import "../assets/main.scss";
   
</style>