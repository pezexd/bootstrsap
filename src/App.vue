<script setup>
const onClick = () => alert('hello world')
</script>

<template>
  <div class="container">
    <div class="row">
      <div class="col">
        <div class="form-group row">
          <div class="col">Nombre:</div>
          <div class="col">
            <strong>cliente.nombre</strong>
          </div>
        </div>
        <div class="form-group row">
          <div class="col">Rut:</div>
          <div class="col">
            <strong>cliente.rut</strong>
          </div>
        </div>
        <div class="form-group row">
          <div class="col">Giro:</div>
          <div class="col">
            <strong>cliente.giro</strong>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="form-group row">
          <div class="col">Grupo:</div>
          <div class="col">
            <strong>cliente.grupo.nombre</strong>
          </div>
        </div>
        <div class="form-group row">
          <div class="col">Activo:</div>
          <div class="col">
            <strong>cliente.activo</strong>
          </div>
        </div>
        <div class="form-group row">
          <div class="col">Fecha Ingreso:</div>
          <div class="col">
            <strong>cliente.base.createAt</strong>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.form-group {
  display: flex;
  justify-content: space-between;
}
</style>
