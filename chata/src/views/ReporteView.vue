<template>
  <div>
     <Navegacion/>
    <table class="table">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">Nombre Del visitante</th>
          <th scope="col">Compañia que representa</th>
          <th scope="col">Persona a quien visita</th>
          <th scope="col">Fecha</th>
          <th scope="col">Hora de salida</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">1</th>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
        </tr>
        <tr>
          <th scope="row">2</th>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
        </tr>
        <tr>
          <th scope="row">3</th>
          <td colspan="2">Larry the Bird</td>
          <td>@twitter</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>

import Navegacion from "../components/Navegacion.vue"
export default {
  name: "ReporteView",
  components: {
    Navegacion
  },
};
</script>

<style>
</style>