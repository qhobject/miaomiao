<template>
  <div id="main">
     <Header title="我的喵喵"></Header>
       <div id="content">
         <Login></Login>
       </div>
      <Tabbar></Tabbar>
  </div>
</template>
<script>
import Header from '@/components/Header'
import Tabbar from '@/components/Tabbar'
import Login  from '@/components/Login'
export default {
  name: 'Mine',
  components : {
      Header,
      Tabbar,
      Login
    }
}
</script>
<style lang="scss" scoped>

</style>

