<script>

export default {
  data() {
    return {x: true}    
  },
}

</script>


<template>
 <h1> hello!!!!!!!!!! </h1>
 <p>Вот так!!! </p>
 <p1> Получилось!!! </p1>
 <p2 v-show="true"> невидимка </p2>
 <p3 v-show="x"> невидимка еще одна </p3>
 <br/>
 <button v-on:click="x=!x"> кнопка </button>
</template>


<style scoped>
h1 {
  color:red;
  }

p1 {
  color:green;
  }
p2 {
  color:blue;
  }

p3 {
  color: brown;
  }

</style>
