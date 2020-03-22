<template>
  <nav>
    <section>
      <div class="left-container">
        <div class="img">
          <img src="../assets/logo.png" alt="logo" />
        </div>
        <div class="logo-text">
          <span>DREAM ELITE</span>
          <br />
          <span>HOMES</span>
        </div>
      </div>
      <ul class="right-container">
        <li>
          <a target="_blank" href="index.html">HOME</a>
        </li>
        <li>
          <a href="#">ABOUT</a>
        </li>
        <li>
          <a href="#">PROJECTS</a>
        </li>
        <li>
          <a href="#">CONTACT</a>
        </li>
      </ul>
    </section>
  </nav>
</template>
<script>
export default {};
</script>
<style scoped>
nav {
  position: relative;
  width: 100%;
  height: 80px;
  margin: 50px auto;
  background-color: #e35175;
}

nav section {
  width: 1170px;
  height: 80px;
  margin: 0 auto;
  /* * background-color: brown;* */
  display: flex;
  justify-content: space-between;
}

nav section .left-container {
  width: 50%;
  height: 80px;
  display: flex;
  justify-content: flex-start;
}

nav section .left-container img {
  position: absolute;
  top: -22px;
}

nav section .logo-text {
  width: 220px;
  height: 60px;
  margin-left: 125px;
  margin-top: 17px;
}

nav .logo-text span {
  font-size: 30px;
  font-weight: 700;
  color: whitesmoke;
}

nav .logo-text span:last-child {
  font-size: 12px;
  color: whitesmoke;
}

nav section .right-container {
  width: 50%;
  height: 80px;
  margin: 0;
  display: flex;
}

nav .right-container li {
  list-style-type: none;
  display: block;
  flex-flow: row wrap;
  justify-content: flex-end;
  box-sizing: border-box;
  width: 100px;
  height: 100%;
  margin: 30px auto;
}

nav .right-container a {
  color: white;
  font-size: 20px;
  font-family: sans-serif;
}

nav .right-container a:link,
a:visited {
  color: white;
  text-decoration: none;
}

nav .right-container a:hover {
  color: rgb(122, 55, 55);
  text-decoration: underline;
}

nav .right-container a:active {
  color: rgb(122, 55, 55);
  text-decoration: none;
}
</style>