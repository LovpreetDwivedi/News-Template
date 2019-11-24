<template>
  <section>
    <div>
      <v-img
        class="center"
        src="https://spiderimg.amarujala.com/assets/images/2019/06/12/au-epaper-logo_5d009e0287ffc.png"
        alt="Center image"
      />
    </div>
    <hr class="hr" />
    <div class="force_login_div">
      <h1>ई-पेपर पढ़ने के लिए कृपया लॉग-इन करें</h1>
    </div>
    <div>
      <a class="force_login force_login_button" href="javascript:void(0);">लॉग-इन करें</a>
    </div>
    <h1 class="epaper-title">
      अभी
      <span class="text_link force_login_button">रजिस्टर करें</span> और अपने शहर की हर खबर, हर समय, हर डिवाइस पर इन खूबियों के साथ पाएं
    </h1>
    <div class="row col-12">
      <div class="col-6">
        <ul>
          <li>
            <h3>डिजिटल-पेपर</h3>
            <p>डिजिटल फार्मेट में जब चाहें अखबार पढ़ें</p>
          </li>
          <li>
            <h3>ई-एडिशन्स</h3>
            <p>सभी संस्करण और मैगजीन्स पढ़ें</p>
          </li>
          <li>
            <h3>पुराने ई-पेपर</h3>
            <p>तारीख चुनें और सभी पुराने अखबार पढ़ें</p>
          </li>
        </ul>
      </div>
      <div class="col-6">
        <ul>
          <li>
            <h3>सभी शहरों के ई-पेपर</h3>
            <p>अपना शहर चुनें और ई-पेपर पढ़ें</p>
          </li>
          <li>
            <h3>अपनी सुविधा अनुसार पढ़ें</h3>
            <p>जब चाहें अपने मोबाइल या डेस्कटॉप पर ताजा संस्करण पाएं</p>
          </li>
          <li>
            <h3>अन्य विशेषताएं</h3>
            <p>अपने पसंदीदा पेज बुकमार्क और शेयर करें</p>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 20%;
}
.force_login_div {
  position: relative;
  overflow: hidden;
  text-align: center;
  font-weight: 700;
  margin: 20px 0 5px;
  line-height: 1.5;
  font-size: 18px;
}

a.force_login {
  width: 165px;
  margin: 10px auto;
  border: 2px solid #17aada;
  padding: 10px 5px 5px;
  text-align: center;
  font-size: 18px;
  box-shadow: 0 6px 8px 0 rgba(213, 213, 213, 0.25);
  border-radius: 5px;
  color: #fff;
  background: #17aada;
  display: block;
  text-decoration: none;
}
.epaper-title {
  margin: 15px 0;
  text-align: center;
  line-height: 1.4;
  font-weight: 700;
}
.text_link {
  color: #dc2829;
  cursor: pointer;
}
li,
ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}
ul li h3 {
  color: #dc2829;
  font-size: 16px;
  margin: 0 0 5px;
  line-height: 1.6;
  font-weight: 700;
  font-size: 30px;
}
ul li {
  color: #221f1f;
  font-size: 16px;
  margin: 0;
  line-height: 1.6;
  font-weight: 700;
  font-size: 23px;
}
ul li {
  position: relative;
  overflow: hidden;
  float: right;
  margin-bottom: 15px;
  padding: 15px;
  padding-left: 48px;
}

ul {
  width: 100%;
}
</style>