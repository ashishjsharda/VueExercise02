<template>
<div>
  <h1> {{isUpperCase ? title.toUpperCase() :title}}</h1>
</div>
</template>

<script>
export default {
  name: 'Exercise1-02',
  data() {
    return {
      title: 'Exercise 1-02',
      message: 'Hello Vue.js!'
    }
  }
}

</script>

