<script>
export default{
    components: (TheHeader,TheFooter)
}
import 'bootstrap/dist/css/bootstrap.min.css'
import TheFooter from './components/TheFooter.vue';
import TheHeader from './components/TheHeader.vue';
</script>

<template>
  <TheHeader></TheHeader>
  <div>
    fsdfgs
  </div>
</template>

<style lang="scss">
  @use './styles/general.scss' as *;
  div{
    background-color: $gg;
  }
</style>
