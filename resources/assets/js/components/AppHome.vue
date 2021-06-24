<template>
  <div>
    <toolbar></toolbar>
    <router-view></router-view>
<!--    <parallex></parallex>-->
    <app-footer></app-footer>
  </div>



</template>
<script>
import Toolbar from './Toolbar'
import AppFooter from './AppFooter'
import Login from './login/Login'
import Parallex from './Parallex'
export default {
  components:{
    Toolbar,AppFooter,Login,Parallex
  }
}
</script>
<style></style>