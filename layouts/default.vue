<template>
  <div>
    <v-header></v-header>
    <nuxt></nuxt>
    <v-footer></v-footer>
  </div>
</template>

<script>
import Header from "~/components/Header"
import Footer from "~/components/Footer"
export default {
  components: {
    'v-header': Header,
    'v-footer': Footer
  }
}
</script>

<style lange="scss">
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
  Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  text-align: center;
  font-size: 20px;
}
*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
li{
  text-decoration: none;
}
.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}
.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}
.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}
.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
.bm-footer{
  color: white;
  background: black;
  line-height: 40px;
  padding: 20px 0;
}
.container{
  display: flex;
  /*flex-direction: column;*/
  height: calc(100vh - 141px);
  /*padding-bottom: 20px;*/
}
.bm-side{
  flex: 0 0 280px;
  background: #d7d9e3;
  padding-top:40px;
}
.bm-con{
  flex: 1;
  text-align: center;
  padding-top:40px;
}
</style>
