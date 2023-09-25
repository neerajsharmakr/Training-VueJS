<template>
  <h1>Test Component</h1>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
  <div id="testing">
    <h1>testing</h1>

    <h1>{{ name }}</h1>
    <br />

    <input type="text" v-model="name" /><br />
  </div>
  <br />
  <div id="btn">
    <button v-on:click="clear">clear</button>
    <button v-on:click="add">Capitilize</button>
  </div>
</template>

<script>
export default {
  name: "TestApp.vue",

  data() {
    return {
      msg: "Hello Neeraj",
      name: "",
    };
  },
  methods: {
    clear: function () {
      this.name = "";
    },
    add: function () {
      this.name = this.name.toUpperCase();
    },
  },
};
</script>

<style></style>
