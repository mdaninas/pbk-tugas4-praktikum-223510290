<script setup>
import Header  from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from "./components/Footer.vue"
</script>

<template>
  <header>
    <Header />
  </header>

  <main>
    <Main />
  </main>

  <footer>
    <Footer />
  </footer>
</template>

<style scoped>
header{
    background: rgb(0, 205, 255);
    background: linear-gradient(118deg, rgba(0, 205, 255, 1) 0%, rgba(255, 16, 16, 1) 52%, rgba(0, 9, 255, 1) 100%);
    height: 80px;
}
main{
  height:800px;
  padding-top: 50px;
  padding-bottom: 50px;
}
footer{
  background-color: blueviolet;
  height: 78px;
}
</style>
