<template>
  <div id="app">
    <Header/>
    <BoardVisual/>
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
import Header from "@/components/Header";
import BoardVisual from"@/components/BoardVisual";
import Footer from"@/components/Footer";


export default {
  name: "App",
  components: {
    Header,
    BoardVisual,
    Footer
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}
</style>
