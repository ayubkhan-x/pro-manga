<template>
  <nav>
    <div class="navbar__big__div container">
      <div class="navbar__read__watch__div">
        <div class="df">
          <img src="../assets/images/glasses.png" alt="">
          <h3>Read Now</h3>
        </div>
        <div class="df">
          <img src="../assets/images/play.png" alt="">
          <h3>Anime Online</h3>
        </div>
      </div>
      <div class="navbar__socials_icons_div">
        <div class="df">
          <h4>Follow Us:</h4>
          <ul class="df">
            <li><a href="#"><img src="../assets/images/reddit.png" alt="">Reddit</a></li>
            <li><a href="#"><img src="../assets/images/twitter.png" alt="">Twitter</a></li>
            <li><a href="#"><img src="../assets/images/discord.png" alt="">Discord</a></li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavbarView"
}
</script>

<style lang="scss">
    nav {
      padding: 0px;
      background: #5F25A6;
      .navbar__big__div {
        display: flex;
        justify-content: space-between;
        height: 58px;

        .navbar__read__watch__div {
          display: flex;
          justify-content: space-between;
          align-items: center;
          color: #fff;
          .df {
            h3 {
              padding-right: 59px;
            }
            img{
              padding-right: 10px;
            }
          }
        }
        .navbar__socials_icons_div {
          display: flex;
          justify-content: space-between;
          align-items: center;
          color: #fff;
          .df {
            h4 {
              font-weight: 700;
              font-size: 20px;
              padding-right: 27.5px;
            }
            ul {
              li {
                font-weight: 500;
                padding-right: 16px;
                font-size: 20px;
                display: flex;
                align-items: center;
              }
            }
            img{
              padding-right: 7.5px;
              height: 17.75px;
              width: 20px;
            }
          }
        }

      }
    }

</style>