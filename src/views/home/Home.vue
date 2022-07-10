<template>
  <div id="home">
    <nav-bar>
      <template v-slot:center>
        购物街
      </template>
    </nav-bar>
  </div>
</template>

<script>
import NavBar from 'components/common/navbar/NavBar'
export default{
  components:{
    NavBar
  }
}
</script>