<template>
<div>
  <Navegacion/>
  <Inicio/>
</div>
  
</template>

<script>
  import Inicio from '../components/InicioCarrusel.vue'
  import Navegacion from '../components/Navegacion.vue'
  export default {
    name: 'Home',
    components: {
     Inicio,
     Navegacion
    },
  }
</script>
