<template>
  <article>
    <title-bar></title-bar>
    <img-gallery></img-gallery>
    <div class="center-title">
      <span>Morbi molestie dolor vel commodo</span>
      <br />
      <span>
        Mentum mauris. orbi vulputate ultrices semper. Phasellus ultricies elit et orcidunt est congue tortor
        vehicul acilisis purus in malesuada purus lacin
      </span>
    </div>
    <div class="content">
      <div class="content-top">
        <div class="img-top">
          <img src="../assets/dwnar.png" />
        </div>
        <h1>Duis felis liberomollis non</h1>
      </div>
      <ul class="content-gallery">
        <li>
          <img src="../assets/e1.jpg" />
          <h2>MANSION HOUSE</h2>
          <p>
            Quisque volutpat odio sit amet mi volutpat, a bibendum ante vulputate. Praesent bibendum lorem
            non sem cursus, eu tempus leo condimentum. Sed nec ullamcorper massa.
          </p>
          <h4>[ Read More..]</h4>
        </li>
        <li>
          <img src="../assets/e2.jpg" />
          <h2>MANSION HOUSE</h2>
          <p>
            Quisque volutpat odio sit amet mi volutpat, a bibendum ante vulputate. Praesent bibendum lorem
            non sem cursus, eu tempus leo condimentum. Sed nec ullamcorper massa.
          </p>
          <h4>[ Read More..]</h4>
        </li>
        <li>
          <img src="../assets/e3.jpg" />
          <h2>MANSION HOUSE</h2>
          <p>
            Quisque volutpat odio sit amet mi volutpat, a bibendum ante vulputate. Praesent bibendum lorem
            non sem cursus, eu tempus leo condimentum. Sed nec ullamcorper massa.
          </p>
          <h4>[ Read More..]</h4>
        </li>
      </ul>
      <div class="anean-top">
        <span>Aenean non mi ac neque rutrum bibendum</span>
        <p>Nunc elementum est ut dignissim posuere</p>
      </div>
      <div class="anean-container">
        <ul class="anean-left">
          <li>
            <img src="../assets/img1.jpg" />
            <div class="text-container">
              <h3>Aenean non miac</h3>
              <h4>- Nunce element</h4>
              <p>Osteger non semper nunc. Nam lacus diam, dignissim eu lobortis sit amet, ultrices sit .</p>
            </div>
          </li>
          <li>
            <img src="../assets/img1.jpg" />
            <div class="text-container">
              <h3>Aenean non miac</h3>
              <h4>- Nunce element</h4>
              <p>Osteger non semper nunc. Nam lacus diam, dignissim eu lobortis sit amet, ultrices sit .</p>
            </div>
          </li>
          <li>
            <img src="../assets/img1.jpg" />
            <div class="text-container">
              <h3>Aenean non miac</h3>
              <h4>- Nunce element</h4>
              <p>Osteger non semper nunc. Nam lacus diam, dignissim eu lobortis sit amet, ultrices sit .</p>
            </div>
          </li>
        </ul>

        <dl class="anean-middle">
          <dt>Maecenas a hendrerit</dt>
          <dd>
            <span>nam at urna quis lacus utre</span>
          </dd>
          <dd>
            <span>nam at urna quis lacus utre</span>
          </dd>
          <dd>
            <span>nam at urna quis lacus utre</span>
          </dd>
          <dd>
            <span>nam at urna quis lacus utre</span>
          </dd>
          <dd>
            <span>nam at urna quis lacus utre</span>
          </dd>
          <dd>
            <span>nam at urna quis lacus utre</span>
          </dd>
          <dd>
            <span>nam at urna quis lacus utre</span>
          </dd>
          <dd>
            <span>nam at urna quis lacus utre</span>
          </dd>
          <dd>
            <span>nam at urna quis lacus utre</span>
          </dd>
        </dl>
        <div class="anean-right">
          <img src="../assets/img6.jpg" alt="111" />
          <div class="text-container">
            <span class="title">Integer Siooni</span>
            <div class="text-content">
              Osteger non semper nunc. Nam lacus diam,
              dignissim eget commodo.
              <span
                style="display: block;width: 1px;height: 10px;"
              ></span>
              Donec faucibus sem a dolor condimentum,
              eget commodo lacus vehicula ellentesque id mauris
              vehicula, porttitor augue vitae, elementum.
            </div>
            <span class="read-more">[ Read More.. ]</span>
          </div>
          <!-- span: 行内元素；div：块级元素 ；规范：行内元素不要包含块级元素 -->
        </div>
      </div>
      <div class="contact-container">
        <ul class="contact-list">
          <li>
            <dl class="Namlacus-dingi">
              <dt>Namlacus dingi</dt>
              <dd>
                <i class="icon-phone"></i>
                <!-- i -> icon -->
                <span>phone:(000) 888 88888</span>
              </dd>
              <dd>
                <i class="icon-envelope"></i>
                <span>info@sitename.com</span>
              </dd>
            </dl>
          </li>
          <li>
            <dl class="Setaliquam-sil">
              <dt>Setaliquam sil</dt>
              <dd>Building name, street number, name of the City, State and Country.</dd>
            </dl>
          </li>
          <li>
            <dl class="Morbi-odio">
              <dt>Morbi odio</dt>
              <dd>
                <input type="text" />
                <button>Subscribe</button>
              </dd>
            </dl>
          </li>
          <li>
            <dl class="Integer-sagitest">
              <dt>Integer sagitest</dt>
              <dd>
                <ul>
                  <li class="icon icon-bird"></li>
                  <li class="icon icon-facebook"></li>
                  <li class="icon icon-candy"></li>
                  <li class="icon icon-google"></li>
                </ul>
              </dd>
            </dl>
          </li>
        </ul>
      </div>
      <div class="footer">
        <p>
          Copyright 2015.Company name All rights reserved.
          <a href="#">网页模板</a>&nbsp;- More Templates
          <a href="#">&nbsp;模板之家</a>
        </p>
      </div>
    </div>
  </article>
</template>
<script>
import TitleBar from "../components/TitleBar.vue";
import ImgGallery from "../components/ImgGallery.vue";
export default {
  components: {
    TitleBar,
    ImgGallery
  }
};
</script>
<style scoped>
.center-title {
  margin: 20px auto;
  height: 132px;
  width: 1200px;
}

.center-title span {
  display: block;
  font-size: 32px;
  font-weight: bold;
  text-align: center;
}

.center-title span:last-child {
  display: block;
  font-size: 25px;
  text-align: center;
  font-weight: 100;
}

.content {
  height: auto;
  width: 100%;
  background-color: #434458;
}

.content .content-top {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}

.content .content-top .img-top {
  position: absolute;
  top: -25px;
}

/**这个图片要怎么使用flex布局居中啊，啊啊啊啊**/
.content .content-top h1 {
  margin-top: 70px;
  width: 450px;
  height: 70px;
  background-color: white;
  color: #e35175;
}

.content .content-gallery {
  width: 1140px;
  height: 500px;
  margin: 60px auto;
  /*8background-color: cornflowerblue;**/
  display: flex;
  justify-content: space-between;
}

.content li {
  list-style-type: none;
}

.content li img {
  width: 350px;
  height: 210px;
}

.content .content-gallery h2 {
  font-family: sans-serif;
  font-weight: normal;
  color: #e35175;
  text-align: center;
}

.content .content-gallery h4 {
  font-family: sans-serif;
  font-weight: lighter;
  color: #e35175;
  font-weight: 0px;
}

.content .content-gallery p {
  line-height: 1.8;
  color: white;
}

.content .anean-top {
  position: relative;
  margin: 70px 0;
  width: 100%;
  height: 170px;
  border: 1px solid #bababa;
  border-left: none;
  border-right: none;
  display: flex;
  flex-direction: column;
  justify-content: center;
  /** background-color: darkcyan;**/
}

.content .anean-top:before {
  content: "";
  position: absolute;
  width: 100%;
  height: 1px;
  top: -8px;
  background-color: #bababa;
}

.content .anean-top:after {
  content: "";
  position: absolute;
  width: 100%;
  height: 1px;
  bottom: -8px;
  background-color: #bababa;
}

.content .anean-top span {
  /**background-color: teal;**/
  margin: 0;
  font-size: 36px;
  font-weight: 700;
  color: white;
  text-align: center;
  display: block;
}

.content .anean-top p {
  margin: 0;
  font-size: 25px;
  font-weight: lighter;
  color: #e35175;
  text-align: center;
}
.anean-container {
  margin: 0 auto;
  width: 1140px;
  height: 522px;
  /**background-color: saddlebrown;**/
  display: flex;
  justify-self: space-between;
}

.anean-container .anean-left {
  margin: 0;
  width: 570px;
  height: 522px;
  /** background-color: rgb(165, 197, 20);**/
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
}

.anean-container .anean-left li {
  list-style-type: none;
  display: flex;
  flex-direction: row;
}

.anean-container .anean-left img {
  width: 177px;
  height: 122px;
  border: 6px solid white;
}

.anean-container .anean-left .text-container {
  width: 335px;
  height: 146px;
  margin-left: 15px;
  line-height: 1.8;
}

.anean-left .text-container h3 {
  margin: 0;
  padding: 0;
  font-size: 25px;
  font-weight: bold;
  color: #f37a8a;
}

.anean-left .text-container h4 {
  margin: 0;
  padding: 0;
  font-size: 18px;
  font-weight: lighter;
  color: #a8a7a7;
}

.anean-left .text-container p {
  margin: 0;
  padding: 0;
  color: #fff;
}

.anean-container .anean-middle {
  margin: 0;
  width: 305px;
  height: 430px;
  /** background-color: turquoise;**/
  display: flex;
  flex-direction: column;
}

.anean-middle dt {
  margin-top: 20px;
  font-size: 25px;
  font-weight: bold;
  color: #f37a8a;
}

.anean-middle dd {
  position: relative;
  margin: 0;
  box-sizing: border-box;
  color: #a8a7a7;
  font-size: 15.4px;
}

.anean-middle dd:after {
  content: "";
  position: absolute;
  left: 0;
  top: 50%;
  width: 7px;
  height: 7px;
  border: 2.5px solid #bf6459;
  border-left: none;
  border-bottom: none;
  transform: translateX(3px) translateY(-3.5px) rotate(45deg);
}

.anean-middle dd span {
  padding: 10px 0 10px 24px;
  box-sizing: border-box;
  display: inline-block;
  border-bottom: 1px solid rgb(202, 197, 197);
  /* text-decoration: underline; */
}

.anean-container .anean-right {
  width: 255px;
  height: 502px;
  /**background-color: rgb(170, 103, 103);**/
  display: flex;
  flex-direction: column;
}

.anean-container .anean-right img {
  width: 243px;
  height: 167px;
  border: 6px solid white;
}

.anean-right .text-container .title {
  display: block;
  margin: 10px auto;
  color: #f37a8a;
  font-size: 25px;
  font-weight: bold;
  text-align: center;
}

.anean-right .text-container .text-content {
  color: #fff;
  font-size: 15.4px;
  display: block;
  line-height: 1.8;
}

.anean-right .text-container .read-more {
  color: #e35175;
  font-weight: lighter;
}

.contact-container {
  width: 100%;
  height: 221px;
  background-color: white;
  display: flex;
  justify-content: center;
  align-items: center;
}

.contact-container .contact-list {
  padding: 0;
  list-style-type: none;
  width: 1140px;
  height: 111px;
  /**  background-color: violet;**/
  display: flex;
  justify-content: space-between;
}

.contact-container li {
  width: 25%;
  height: 100%;
  /**  background-color: aqua;**/
}

.contact-container dt {
  color: rgb(67, 68, 88);
  font-size: 24px;
  font-weight: bold;
}

.contact-container dd {
  padding: 0;
  margin: 0;
  font-size: 15.4px;
  color: #868797;
}

.contact-container .Namlacus-dingi i {
  width: 20px;
  height: 20px;
  display: inline-block;
  background-color: #868797;
  background-image: url("../assets/img-sprite.png");
  transform: translateY(5px);
}

.icon-phone {
  background-position: 2px -6px;
}

.icon-envelope {
  background-position: -1px -37px;
}

.contact-container .Setaliquam-sil {
  max-width: 255px;
}

.contact-container .Morbi-odio dd {
  display: flex;
  flex-direction: row;
}

.contact-container .Morbi-odio input {
  width: 140px;
  height: 36px;
  border: 1px solid #e35175;
}

.contact-container .Morbi-odio button {
  width: 87px;
  height: 40px;
  color: #e1e1e1;
  background-color: #f37a8a;
  font-size: 15.4px;
  border: none;
}

.contact-container .Integer-sagitest ul {
  margin: 0;
  padding: 0;
  list-style-type: none;
  display: flex;
  flex-direction: row;
}

.contact-container .Integer-sagitest .icon {
  width: 48px;
  height: 48px;
  /**  background-color: blue;**/
  background-image: url("../assets/social-icons.png");
}

.icon-bird {
  background-position: -45px 5px;
}

.icon-facebook {
  background-position: -45px -43px;
}

.icon-candy {
  background-position: -45px -91px;
}

.icon-google {
  background-position: -45px -139px;
}

.footer {
  width: 100%;
  height: 112px;
  background-color: rgb(67, 68, 88);
}

.footer p {
  color: #868797;
  text-align: center;
  padding-top: 50px;
}

.footer a:link,
a:visited {
  text-decoration: none;
  color: rgb(228, 95, 115);
}

.footer a:hover,
a:active {
  text-decoration: underline;
  color: rgb(100, 100, 34);
}
</style>