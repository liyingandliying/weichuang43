<template>
  <div>
      <h1>用户详情</h1>
      <!-- <p>用户名：{{$route.query.name}}</p>
      <p>用户id:{{$route.query.id}}</p>
       <p>用户id:{{params.id}}</p> -->
       <p>用户名{{$route.params.name}}</p>
       <p>用户id{{$route.params.id}}</p>
  </div>
</template>

<script>
export default {
    data() {
        return {
            params:this.$route.params,

        }
    },

}
</script>

<style lang="scss" scoped>

</style>