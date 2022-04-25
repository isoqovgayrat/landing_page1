<template>

  <div id="app">
    <NavbaR />
    <JumbotroN/>
    <CTA/>
    <CardS/>
    <FooteR/>
  </div>
</template>

<script>
import NavbaR from './components/NavbaR.vue'
import JumbotroN from './components/JumbotroN.vue'
import CTA from './components/CTA.vue'
import CardS from "@/components/CardS";
import FooteR from "@/components/FooteR";

export default {
  name: 'App',
  components: {
    FooteR,
    CardS,
    NavbaR,
    JumbotroN,
    CTA
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}
</style>
