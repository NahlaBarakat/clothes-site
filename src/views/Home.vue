<template>
  <div >
    <div class="home" >
     <router-link to="/bags" class="link">bags</router-link>
     <router-link to="/dress" class="link">dress</router-link>
  </div>
  <div>
   <router-view/>
   </div>
  <div>
   <img src="dress5.jpg"/>
   <img src="bag5.jpg"/>
        <img src="dress6.jpg"/>
         <img src="bag4.jpg"/>
        <img src="dress3.jpg"/>
        <img src="bag1.jpg"/>
         <img src="bag2.jpg"/>
  </div>
  
   </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'home',
  components: {
    
  }
}
</script>
<style scoped>
.home{
  background-color:pink;
}
.link{
  display:inline-block;
  margin-left:15px;
  font-weight:bold;
  font-family:sofia;
  font-size:15px;
}
</style>