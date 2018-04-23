<template>
  <div>
    <h1>compTwo html</h1>
    <h1>姓名:{{$route.params.name}}</h1>
    <h1>年龄:{{$route.params.age}}</h1>

  </div>

</template>
<script>
  export default {
    name:'CompTwo',
    beforeRouteEnter:(to,from,next)=>{
      console.log("进入comp2");
      next()
    },
    beforeRouteLeave:(to,from,next)=>{
      console.log("离开comp2");
      next()
    }
  }
</script>
<style scoped>

</style>
