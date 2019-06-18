<template>
<form class="w-50 text-center moveCenterForm">
  <div class="form-group text-center inline-block mr">
    <label for="exampleFormControlInput1">Correo Electronico</label>
    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
  </div>
   <div class="form-group">
    <label for="exampleFormControlInput1">Titulo de mensaje</label>
    <input type="text" class="form-control" placeholder="Titulo">
  </div>
  <div class="form-group">
    <label for="exampleFormControlTextarea1">Contenido</label>
    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" placeholder="Contenido"></textarea>
  </div>
  <div class="form-group">
    <button type="button" class="btn btn-primary">Enviar</button>
  </div>
</form>
</template>

<style scoped>
.moveCenterForm{
  margin-left: 25%;
}
</style>
