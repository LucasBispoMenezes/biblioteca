<template>
  <div class="container d-flex flex-row justify-content-evenly align-items-center ">
    <h1>Biblioteca</h1>
    <input type="text" class="form-control" placeholder="Pesquisar por título" />
    <button class="btn btn-outline-success" data-bs-toggle="modal" data-bs-target="#CreateBook">adicionar</button>
  </div>
</template>

<style lang="css" scoped>
input {
  height: 40px;
  width: 300px;
}
</style>