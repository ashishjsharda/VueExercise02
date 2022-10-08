<template>
  <div>
    <h1> {{isUpperCase ? title.toUpperCase() :title}}</h1>
  </div>
</template>

<script>

export default {

  data() {

    return {

      title: 'My first component!',
      isUpperCase: false,

    }

  },

}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
