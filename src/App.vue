<template>

  <div id="app" class="container">
    
    <card
      data-image="https://images-na.ssl-images-amazon.com/images/I/91M0isciFtL.jpg"
    >
      <h1 slot="header">Conspiracies</h1>
      <p slot="content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
    </card>
    <card
      data-image="https://steamcdn-a.akamaihd.net/steam/apps/911400/header.jpg?t=1553879054"
    >
      <h1 slot="header">AC 3</h1>
      <p slot="content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
    </card>
    <card
      data-image="https://4.bp.blogspot.com/-xeJ3Mx0Oyno/WodxowiQdhI/AAAAAAAAAw0/LTv7DWGBmo4T2gnmGtVmfagYopOnY8zBwCLcBGAs/w1200-h630-p-k-no-nu/assassin-s-creed-brasil-personagem-by-diogocarneir_njkc.1920.jpg"
    >
      <h1 slot="header">AC Brasil</h1>
      <p slot="content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
    </card>
    <card
      data-image="https://cdn.gamer-network.net/2020/articles/2020-05-08-11-19/AC_Valhalla_logo.png/EG11/thumbnail/1920x1080/format/jpg/quality/80"
    >
      <h1 slot="header">Ac Valhalla</h1>
      <p slot="content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
    </card>
  </div>
</template>

<script>
import Card from './components/Card'

export default {
  name: "App",
  components: {
    Card,
  },
};
</script>

<style>

</style>
