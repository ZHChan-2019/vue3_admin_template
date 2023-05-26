<script setup lang="ts">

import { reactive } from "vue";

var obj = reactive({
  name :"hello"
});

</script>

<template>
  <div class="box">{{obj.name}}</div>
</template>

<style scoped>
.box{
  width: 20px;
  height: 500px;background-color: aqua;
}
</style>
