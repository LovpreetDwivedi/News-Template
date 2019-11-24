<template>
  <section>
    <header>
      <nav>
        <ul>
          <img
            class="img"
            src="https://www.pnglot.com/pngfile/detail/5-54700_download-png-facebook-twitter-instagram-youtube-logo.png"
            alt="logo.png"
          />
          <li>
            <nuxt-link to="/">Hindi News</nuxt-link>
          </li>
          <li>
            <nuxt-link to="Epaper">Epaper</nuxt-link>
          </li>
          <li>
            <nuxt-link to="app">Download my app</nuxt-link>
          </li>
        </ul>
        <div class="col-3 thumbnail">
          <img src="https://spiderimg.amarujala.com/assets/img/au-logo.png" alt="logo.png" />
        </div>
        <div class="col-xl-12 head">
          <div>
            <li>
              <nuxt-link to="/">Home</nuxt-link>
            </li>
            <li>
              <nuxt-link to="Country">Country</nuxt-link>
            </li>
            <li>
              <nuxt-link to="Entertenment">Entertenment</nuxt-link>
            </li>
            <li>
              <nuxt-link to="Astrology">Astrology</nuxt-link>
            </li>
            <form>
              <input type="text" name="search" placeholder="Search.." />
            </form>
          </div>
        </div>
      </nav>
    </header>
    
  </section>
</template>

<script>
export default {};
</script>

<style>
li a {
  color: rgb(109, 105, 105);
  text-decoration: none;
  float: left;
  padding: 10px;
}

ul {
  list-style-type: none;
}

li {
  display: inline;
}

.img {
  width: 120px;
  height: 100%;
  float: left;
}

.head {
  background-color: rgb(17, 15, 15);
}

input[type="text"] {
  width: 130px;
  box-sizing: border-box;
  border: 2px solid #ccc;
  border-radius: 4px;
  font-size: 16px;
  background-color: white;
  background-position: 10px 10px;
  background-repeat: no-repeat;
  padding: 12px 20px 12px 40px;
  -webkit-transition: width 0.4s ease-in-out;
  transition: width 0.4s ease-in-out;
}

input[type="text"]:focus {
  width: 40%;
}

.image {
  height: 50px;
  width: 40px;
  float: right;
  margin: 10px;
}

</style>