<template>
  <div>
    <navbar />
    <nuxt />

  </div>
</template>
<script>
export default {
  components:{
  navbar: () => import('./navbar')
  }
}
</script>


<style>

</style>
