<template>
  <div class="form">
    
    <div class="input-group mb-3">
      <span class="input-group-text" id="inputGroup-sizing-default"
        >Nombre Del Visitante:</span
      >
      <input
        type="text"
        class="form-control"
        aria-label="Sizing example input"
        aria-describedby="inputGroup-sizing-default"
      />
      <div class="input-group mb-3">
        <span class="input-group-text" id="inputGroup-sizing-default"
          >Compañia que representa:</span
        >
        <input
          type="text"
          class="form-control"
          aria-label="Sizing example input"
          aria-describedby="inputGroup-sizing-default"
        />
      </div>
      <select class="form-select" aria-label="Default select example">
        <option selected>Persona a Quien visita:</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
    </div>
    <div>
      <div class="input-group mb-3">
        <span class="input-group-text" id="inputGroup-sizing-default"
          >Fecha:</span
        >
        <input
          type="date"
          class="form-control"
          aria-label="Sizing example input"
          aria-describedby="inputGroup-sizing-default"
        />
      </div>
      <div class="input-group mb-3">
        <span class="input-group-text" id="inputGroup-sizing-default"
          >Hora de salida:</span
        >
        <input
          type="time"
          class="form-control"
          aria-label="Sizing example input"
          aria-describedby="inputGroup-sizing-default"
        />
      </div>
      <button type="button" class="btn btn-primary">Registrar</button>
    </div>
    
  </div>
</template>

<script>
export default {};


</script>

<style>
.form {
 width: 500px;
 height: 400x;
 text-align: center;
 margin-left: auto;
 margin-right: auto;
 margin-top: 35px;
}
.input-group{
  margin-top: 15px;
}

</style>