<template>
  <div>
    <s-nav></s-nav>
    <div style="height: 300px;background-color: red"></div>
    <s-footer></s-footer>
  </div>

</template>

<script>
  import SNav from "../components/nav"
  import SFooter from "../components/footer"
  export default {
    name: "chan",
    components:{
      SNav,SFooter
    },
    data(){
      return {
        msg:""
      }
    }
  }
</script>

<style scoped>

</style>
