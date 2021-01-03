<template>
  <div id="app">
    <Header/>
    <Body/>
    <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header';
import Body from "@/components/Body";
import Footer from "@/components/Footer";

export default {
  name: 'App',
  components: {
    Footer,
    Body,
    Header
  },
  methods: {},
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  font-family: "SF Pro SC","SF Pro Display","SF Pro Icons","PingFang SC","Helvetica Neue","Helvetica","Arial",sans-serif;;
}

#app {

}
</style>
