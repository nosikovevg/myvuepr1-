<script>

const z = {
  data() {
    x: true
  },
}

</script>


<template>
 <h1> hello!!!!!!!!!! </h1>
 <p>Вот так!!! </p>
 <p1> Получилось!!! </p1>
 <p2 v-show="false"> невидимка </p2>
 <p3 v-show="x"> невидимка еще одна </p3>
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
  color:pink;
  }

</style>
