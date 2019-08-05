<template>
    <div class="cover">
        <!-- dsf -->
        <Navbar/>
        <img class="cover-grass" src="../assets/img/grass.png" alt="">
        <img class="cover-female" src="../assets/img/female.png" alt="">
        <img class="cover-leaf" src="../assets/img/leaf.png" alt="">

        <div class="cover-sentence">
            <h1>OUTDOOR</h1>
            <h2>ACTIVITIES</h2>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
            </p>
        </div>
    </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'cover',
  components: {
    Navbar
  }
}
</script>
