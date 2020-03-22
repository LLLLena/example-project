<template>
  <div>
    我是组件
    <button @click="$emit('emitFunc',test)">{{ name }}</button>
    {{test}}
  </div>
</template>
<script>
export default {
  name: "NaNa",
  props: {
    name
  },

  data() {
    return {
      test: "组件内变量"
    };
  }
};
</script>