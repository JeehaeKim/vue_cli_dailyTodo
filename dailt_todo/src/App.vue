<template>

  <!-- 가상요소 만들기, import한 뷰 컴포넌트 갖다놓기??-->
  <!-- 컴포넌트는 곡 div로 묶는다 -->
  <div id="app">
    <header-component></header-component>
    <input-component></input-component>
    <list-component></list-component>
    <footer-component></footer-component>
  </div>

</template>

<script>
  import HeaderComponent from './components/HeaderComponent.vue'
  import InputComponent from './components/InputComponent.vue'
  import ListComponent from './components/ListComponent.vue'
  import FooterComponent from './components/FooterComponent.vue'

  export default {
    name: 'App',
    components: {
      'header-component': HeaderComponent,
      'input-component':InputComponent,
      'list-component':ListComponent,
      'footer-component':FooterComponent
    }
  }
</script>

<style>
</style>
