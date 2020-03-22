<template>
  <div id="app">
    <pink-property></pink-property>
    <!-- <div v-if="displayVal">v-if的指令栗子{{ displayVal }}</div>
    <button :class="{'change': displayVal}" @click="clickBtn">显示/隐藏 v-if元素</button>
    <div v-show="displayVal">v-show的指令栗子{{ displayVal }}</div>
    <ul>
      <li v-for="(item,index) in ulList" :key="index">{{item.name}} {{++index}}</li>
    </ul>
    <hello-world nana="我叫娜娜~~"></hello-world>
    <na-na name="nana" @emitFunc="emitFunction($event,test)"></na-na>
    <section>
      <div>用户的输入: {{ userInput }}</div>
      <input type="text" v-model="userInput" />
    </section>-->
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
// import NaNa from "./components/NaNa.vue";

import pinkProperty from "./pages/pinkProperty.vue";

export default {
  name: "App",
  components: {
    // HelloWorld,
    // NaNa,
    pinkProperty
  },
  //data(){}对象方法的简写 相当于data:function(){}
  data() {
    return {
      userInput: "",
      displayVal: false,
      ulList: [
        {
          name: "li"
        },
        {
          name: "li"
        },
        {
          name: "li"
        },
        {
          name: "li"
        },
        {
          name: "li"
        },
        {
          name: "li"
        },
        {
          name: "li"
        }
      ]
    };
  },
  methods: {
    //key: value
    clickBtn: function() {
      console.log("执行事件");
      this.displayVal = !this.displayVal;
    },
    emitFunction: function(test = "aaa") {
      console.log("子组件要执行的方法", test);
    }
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.change {
  color: red;
}
</style>
