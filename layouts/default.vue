<template>
  <div>
    <Nav />
    <Nuxt />
    <footer>
      <div class="row col-12 news-bg h">
        <nuxt-link to="/wether">
          <p>Download</p>
        </nuxt-link>
        <nuxt-link to="/app">
          <img class="logo" src="http://pngimg.com/uploads/android_logo/android_logo_PNG32.png" alt />
        </nuxt-link>
        <nuxt-link to="/app">
          <img class="logo" src="http://pngimg.com/uploads/apple_logo/apple_logo_PNG19679.png" alt />
        </nuxt-link>
        <nuxt-link to="/app">
          <img
            class="logo"
            src="https://www.freepngimg.com/thumb/google/67045-play-google-newsstand-android-free-transparent-image-hq.png"
            alt
          />
        </nuxt-link>
        <img
          class="center logo"
          src="https://spiderimg.amarujala.com/assets/img/au-logo.png"
          alt="Center logo"
        />
      </div>
      <div class="row col-12">
        <div class="col-2 h">
          <nuxt-link to="/app">
            <p>News From Indian States</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Uttar Pradesh News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Himachal Pradesh News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Uttarakhand News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Haryana News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Bihar News</p>
          </nuxt-link>
        </div>
        <div class="col-2 h">
          <nuxt-link to="/app">
            <p>Sports News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Cricket News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Live Cricket Score</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Hockey</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Tennis</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Football</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Tools</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Age Calculator</p>
          </nuxt-link>
        </div>
        <div class="col-2 h">
          <nuxt-link to="/app">
            <p>Lifestyle</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Health News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Fitness News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Fashion News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Spirituality</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Astrology</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Astrologers</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Pujas</p>
          </nuxt-link>
        </div>
        <div class="col-2 h">
          <nuxt-link to="/app">
            <p>Entertainment News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Bollywood News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>TV Serials</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Hollywood News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Movie Reviews</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Photo Gallery</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Videos</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Hindi Jokes</p>
          </nuxt-link>
        </div>
        <div class="col-2 h">
          <nuxt-link to="/app">
            <p>Latest News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Technology News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Auto News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Business News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Europe News</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Education</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Sarkari Result</p>
          </nuxt-link>
          <nuxt-link to="/app">
            <p>Gadgets</p>
          </nuxt-link>
        </div>
        <div class="col-2 h">
          <img
            class="imge"
            src="https://spiderimg.amarujala.com/assets/images/2018/02/12/epaper_5a8156ee0c2d1.png"
            alt="Center image"
          />
        </div>
      </div>
      <div class="news-bg">
        <p>
          Read the latest and breaking
          <b>Hindi news</b> amarujala.com. Get live Hindi news about India and the World from politics, sports, bollywood, business, cities, lifestyle, astrology, spirituality, jobs and much more.
          <b>Register with amarujala.com</b> get all the latest Hindi news updates as they happen.
        </p>
      </div>
      <p>Other Properties: Firkee My Result Plus Safalta TAMS Safalta Class SSC Coaching</p>
    </footer>
  </div>
</template>
<script>
import Nav from "./nav/nav";
export default {
  components: {
    Nav
  }
};
</script>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
.logo {
  height: 30px;
  width: 20px;
  margin: 5px;
}
</style>
