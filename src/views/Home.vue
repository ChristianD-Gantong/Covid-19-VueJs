<template>
  <div class="home">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <TopPage></TopPage>
    <information></information>
    <prevention></prevention>
  </div>

</template>

<script>
// @ is an alias to /src
import TopPage from '@/components/TopPage.vue'
import information from '@/components/Information.vue'
import prevention from '@/components/Prevention.vue'
export default {
  name: 'Index',
  components: {
    TopPage,
    information,
    prevention
  }
}
</script>

<style scoped>

</style>