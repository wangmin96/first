<template>
  <div>
    <h1>Comp1 page!</h1>
    <h1>{{$route.params.name}}</h1>
    <h1>{{$route.params.age}}</h1>
    <router-view/>
  </div>
</template>

<script>
  export default {
    name:"Comp1"
  }
</script>

<style scoped>

</style>
