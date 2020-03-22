<template>
  <ul class="img-gallery">
    <li v-for="(item,index) in imgList" :key="index">
      <img :src="item.imgPath" alt />
    </li>
    <!-- <li>
      <img src="../assets/img1.jpg" />
    </li>
    <li>
      <img src="../assets/img2.jpg" />
    </li>
    <li>
      <img src="../assets/img3.jpg" />
    </li>
    <li>
      <img src="../assets/img4.jpg" />
    </li>
    <li>
      <img src="../assets/img5.jpg" />
    </li>
    <li>
      <img src="../assets/img6.jpg" />
    </li>-->
  </ul>
</template>
<script>
export default {
  name: "ImgGallery",
  data() {
    return {
      imgList: [
        {
          imgPath: require("../assets/img1.jpg")
        },
        {
          imgPath: require("../assets/img2.jpg")
        },
        {
          imgPath: require("../assets/img3.jpg")
        },
        {
          imgPath: require("../assets/img4.jpg")
        },
        {
          imgPath: require("../assets/img5.jpg")
        },
        {
          imgPath: require("../assets/img6.jpg")
        }
      ]
    };
  }
};
</script>
<style scoped>
.img-gallery {
  width: 1164px;
  height: 536px;
  margin: 80px auto;
  background-color: coral;
  padding: 0px;
  display: flex;
  flex-wrap: wrap;
}

.img-gallery li {
  list-style-type: none;
}

.img-gallery li img {
  display: block;
  margin: 0;
}
</style>