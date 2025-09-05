<template>
  <section class="tabla-usuarios">
    <h2 class="tabla-usuarios__titulo">Tabla</h2>
    <table class="table table-bordered tabla-usuarios__tabla" role="table" aria-describedby="tablaUsuariosTitulo">
      <caption id="tablaUsuariosTitulo">Lista de usuarios registrados</caption>
      <thead>
        <tr>
          <th>Nombre</th>
          <th>Apellido</th>
          <th>Fecha de nacimiento</th>
          <th>Edad</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Millaray</td>
          <td>Lorca</td>
          <td>1990-05-12</td>
          <td>35</td>
        </tr>
        <tr>
          <td>Felipe</td>
          <td>Gatica</td>
          <td>1985-03-22</td>
          <td>40</td>
        </tr>
        <tr>
          <td>Javiera</td>
          <td>Troncoso</td>
          <td>2000-08-10</td>
          <td>25</td>
        </tr>
      </tbody>
    </table>
  </section>
</template>

<script>
export default {
  name: 'TablaUsuarios'
};
</script>

<style scoped>
.tabla-usuarios {
  background-color: #ffffff;
  padding: 2rem;
  border-radius: 8px;
}

.tabla-usuarios__titulo {
  color: #6a1b9a;
  font-size: 1.8rem;
  margin-bottom: 1rem;
  text-align: center;
}

.tabla-usuarios__tabla th,
.tabla-usuarios__tabla td {
  color: #6a1b9a;
  background-color: #fdfdfd;
  text-align: center;
  vertical-align: middle;
}

.tabla-usuarios__tabla th {
  font-weight: bold;
}
</style>
