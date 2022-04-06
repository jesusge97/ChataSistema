<template>
<v-containter >
    <div class="abs-center">
  <v-carousel>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
      
    >
    <v-row
          class="fill-height"
          align="center"
          justify="center"
        >
          <div class="boton">
            
          </div>
          
        </v-row>
        
        
    </v-carousel-item>
    
  </v-carousel>
  </div>
</v-containter>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: require("../assets/inicioF1.png") ,
          },
          {
            src: require("../assets/inicioF2.png") ,
          },
          {
            src: require("../assets/inicioF3.png") ,
          },
          {
            src: require("../assets/inicioF4.png") ,
          },
          
        ],
        
      }
    },
  }
</script>

<style>
.abs-center {
  margin-left: 300px;
  margin-right: 300px;
  margin-top: 40px;
}
.texto{
margin-left: 450px;
  margin-top: 40px;
  font-size: 30px;
}
</style>