<template>
  <section id="footer">

    <div class="footer-wrap">
      <div class="container">
          <!-- FOOTER MENU LEFT -->
          <div class="left">
              <ul>
                  <h4>Dc Comics</h4>
                  <li v-for="(links, indexDc) in dcComicsLink" :key="indexDc">
                      <a href="#"> {{links.linkDc}} </a>
                  </li>

                  <h4>Shop</h4>
                  <li v-for="(links, indexShop) in shopLink" :key="indexShop">
                      <a href="#">{{links.linkShop}}</a>
                  </li>
              </ul>

              <ul>
                  <h4>Dc</h4>
                  <li v-for="(links, indexDcMenu) in dcmenuLink" :key="indexDcMenu">
                    <a href="#">{{links.linkDcMenu}}</a>
                  </li>
              </ul>

              <ul>
                  <h4>Sites</h4>
                  <li v-for="(links, indexSites) in sitesMenu" :key="indexSites">
                      <a href="#">{{links.linkSites}}</a>
                  </li>
              </ul>
          </div>

          <!-- FOOTER IMG RIGHT -->
          <div class="right">
          </div>
      </div>
    </div>

    <!-- FOOTER BAR SIGNUP e SOCIAL -->
    <div class="footer-bar">
        <div class="container">

            <!-- SEZIONE SINISTRA SIGNUP -->
            <div class="signup-foot">
                <a href="#">Sign-up now!</a>
            </div>

            <!-- SEZIONE DESTRA SOCIAL -->
            <div class="social-group">
                <h3>Follow Us</h3>
                <ul>
                    <li v-for="(icons, index) in social" :key="index">
                      <a href=""><i :class="icons.icon"></i></a>
                    </li>
                </ul>
            </div>
        </div>
    </div>

  </section>
</template>

<script>
  export default {
    name: 'FooterDc',
    data() {
    
      return {

        dcComicsLink: [
        
          {
            linkDc: 'Characters',
          },
          {
            linkDc: 'Comics', 
          },
          {
            linkDc: 'Movies',
          },
          {
            linkDc: 'TV', 
          },
          {
            linkDc: 'Games',
          },
          {
            linkDc: 'Videos', 
          },
          {
            linkDc: 'News', 
          },
        ],

        shopLink: [

          {
            linkShop: 'Shop DC',
          },
          {
            linkShop: 'Shop DC Collectibles',
          },
        
        ],

        dcmenuLink: [
            {
              linkDcMenu: 'Terms of Use',
            },
            {
              linkDcMenu: 'Privacy policy (New)',
            },
            {
              linkDcMenu: 'Ad Choices',
            },
            {
              linkDcMenu: 'Advertising',
            },
            {
              linkDcMenu: 'Jobs',
            },
            {
              linkDcMenu: 'Subscriptions',
            },
            {
              linkDcMenu: 'Talent Workshops',
            },
            {
              linkDcMenu: 'CPSC Certificates',
            },
            {
              linkDcMenu: 'Ratings',
            },
            {
              linkDcMenu: 'Shop Help',
            },
            {
              linkDcMenu: 'Contact Us',
            },
        ],

        sitesMenu: [
        
          {
            linkSites: 'DC',
          },
          {
            linkSites: 'MAD Magazine',
          },
          {
            linkSites: 'DC Kids',
          },
          {
            linkSites: 'DC Universe',
          },
          {
            linkSites: 'DC Power Visa',
          },

        ],

        social: [
        
          {
            icon: 'fa-brands fa-facebook-f',
          },

          {
            icon: 'fa-brands fa-twitter',
          },

          {
            icon: 'fa-brands fa-youtube',
          },

          {
            icon: 'fa-brands fa-pinterest-p',
          },

          {
            icon: 'fa-brands fa-periscope',
          },
        
        ], 
      
      }
    
    },
  }
</script>

<style lang="scss" scoped>
    @import "../assets//style/footer.scss";
</style>