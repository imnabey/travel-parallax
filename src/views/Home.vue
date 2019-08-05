<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Cover/>
    <Yoga/>
  </div>
</template>

<script>
import Cover from '@/components/Cover.vue'
import Yoga from '@/components/Yoga.vue'

export default {
  name: 'home',
  components: {
    Cover,
    Yoga
  }
}
</script>
