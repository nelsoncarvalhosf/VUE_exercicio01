<template>
  <div id="app">
    <Cabecalho msg="Welcome"/>
    <Menu msg="Menu de Navegação"/>
    <Conteudo msg="What is Lorem Ipsum?"/>
    <Sidebar msg="Mais Posts"/>
  </div>
</template>

<script>
import Cabecalho from './components/Cabecalho.vue'
import Menu from './components/Menu.vue'
import Conteudo from './components/Conteudo.vue'
import Sidebar from './components/Sidebar.vue'

export default {
  name: 'App',
  components: {
    Cabecalho,
    Menu,
    Conteudo,
    Sidebar
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
  width: 90%;
  margin: 60px auto 0;
  border: 1px solid #000;
}
</style>
