<template>
    <div class="content_box">
      <p class="main-con">这是内容{{$route.params.blog}}</p>
      <div><nuxt-link to="/">首页</nuxt-link></div>
    </div>
</template>

<script>
export default {
  validate({params}) {
    return !isNaN(+params.blog)
  }
}
</script>

<style scoped>
.main-con{
  text-align: center;
  padding: 50px;
  margin: 0 auto;
}
.content_box{
  display: flex;
  flex-direction: column;
  padding-bottom: 20px;
}
</style>
