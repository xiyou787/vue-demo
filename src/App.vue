<template>
  <div>
    <a :href="url">点击去{{ name }}</a>
    <input type="text" v-model="name" />
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: "百度",
      url: "www.baidu.com",
    };
  },
};
</script>

<style>
</style>