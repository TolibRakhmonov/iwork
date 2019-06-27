<template>
  <div>
    <navbar />
    <nuxt />
    <Footer />
  </div>
</template>
<script>
export default {
  components:{
  navbar: () => import('./navbar'),
  Footer: () => import('./footer')
  }
}
</script>


<style>

</style>
