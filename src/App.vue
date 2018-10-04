<template>
  <div id="app" class="container">
    <img alt="Vue logo" class="logo" src="./assets/logo.png">
    <TodoList></TodoList>
  </div>
</template>

<script>
  import TodoList from './views/TodoList.vue'

  export default{
    name: 'App',
    components: {
      TodoList,
    }
  }
</script>


<style lang="scss">
*{
  box-sizing: border-box;
}

.container{
  max-width: 600px;
  margin: 0 auto;
}

.logo{
  display: block;
  margin: 20px auto;
  margin-top: 60px;
  height: 75px;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  color: #2c3e50;
  font-size: 24px;
  margin-top: 60px;
}

</style>
