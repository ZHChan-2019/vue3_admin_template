<script setup lang="ts">
import { reactive } from 'vue'

let obj = reactive({
  name: 'hello',
})

var fun=>()
{
  console.log('只是未格式化代码')
}

</script>

<template>
  <div class="box">{{ obj.name }}</div>
</template>

<style scoped>
.box {
  width: 200px;
  height: 500px;
  background-color: aqua;
}
</style>
