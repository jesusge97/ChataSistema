<template>
  <div>
    <Navegacion />
    <div class="home">
      <div>
        <img class="img-chata" src="../assets/chata2.png" />
        <div class="titulo">Registra tu visita</div>
        <div class="titulo2">Llene el siguiente formulario correctamente</div>
      </div>
      <FormularioVisita />
      

    </div>
  </div>
</template>

<script>
import FormularioVisita from "../components/FormularioVisita.vue";
import Navegacion from "../components/Navegacion.vue";

export default {
  name: "HomeView",
  components: {
    FormularioVisita,
    Navegacion,
   
  },
};
</script>
<style scoped>
.img-chata {
  display: block;
  margin: auto;
  max-width: 100%;
  width: 200px;
}
.home {
  font-family: "Anton", sans-serif;
  color: #29b6f6;
  text-align: center;
  font-size: 25px;
}
.titulo {
  color: black;
  margin-top: 30px;
}
.titulo2 {
  color: black;
  margin-top: 10px;
  font-size: 20px;
}
</style>