<script>
export default{
    components: {TheHeader,TheFooter,Jumbotron,Section1}
};
import 'bootstrap/dist/css/bootstrap.min.css'
import TheFooter from './components/TheFooter.vue';
import TheHeader from './components/TheHeader.vue';
import Jumbotron from './components/Jumbotron.vue';
import Section1 from './components/Section1.vue';
</script>

<template>
  <div class="d-flex flex-column height">
    <TheHeader></TheHeader>
    <Jumbotron class="flex-grow-1"></Jumbotron>
    <Section1 ></Section1>
    <TheFooter></TheFooter>
  </div>
</template>

<style lang="scss">
  @use './styles/general.scss' as *;

  *{
    font-family: sans-serif;
  }

  li{
    list-style-type: none;
}

  a{
    text-decoration: none;
  }

  img{
    width: 100%;
  }

  .height{
    height: 100vh;
  }
</style>
