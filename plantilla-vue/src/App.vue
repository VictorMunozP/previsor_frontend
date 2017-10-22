<template>
  <div>
    <header>
      <div class="branding">
        <img class ="logo-small" src="./img/PreVisor_logo_vector.svg" />
        <!-- <span>Nagevación superior</span> -->
      </div>
      <nav>
        <a href="#/">Home</a>
        <a href="#/uno">Valoraciones</a>
        <a href="#/grafic">Comparacion Prestadores</a>
        <a href="#/admin">Administración</a>


      </nav>

    </header>

    <main class="container">
      <router-view></router-view>
    </main>


    <footer>
      Grupo 7 - Taller de base de datos - 2do semestre 2017
    </footer>
</div>
</template>

<script>


</script>
