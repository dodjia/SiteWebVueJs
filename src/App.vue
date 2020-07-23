<template>
  <div class="header">
    <div class="textHeader">
      <nav class="navbar navbar-expand-lg navbar-dark">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse d-flex justify-content-center" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="#">Accueil<span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Enfants</a>
            </li><li class="nav-item">
            <a class="nav-link" href="#">Adolescentes</a>
          </li><li class="nav-item">
            <a class="nav-link" href="#">Femmes</a>
          </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Hommes</a>
            </li>
          </ul>
        </div>
      </nav>
      <div class="prenom">
        <p class="d-flex justify-content-center">Estelle   Lesein </p>
        <p class="d-flex justify-content-center profession">Psychologue clinicienne</p>
      </div>
      <div class="infos">
        <p>
          La psychologie et le développement personnel est un choix de vie pour moi. Après un parcours professionnel dans de multiples domaines,
          j’ai choisi de reprendre mes études à l’âge de 34  ans par vocation. L’humain est pour moi une véritable source d’inspiration et ma passion est de l’accompagner autant qu’il m’est possible,
          vers la prise de conscience de ses potentiels et de ses multiples possibilités.
        </p>
      </div>
    </div>
  </div>

</template>

<style lang="scss">
  html, body{
    margin: 0;
    padding: 0;
  }
  .header {
    height: 800px;
    display: block;
    background-image: url(assets/images/fond2.jpg);
    background-size: cover;
    background-attachment: fixed;
    color: white;
  }
  .navbar{
    display: flex;
    color: white;
    text-decoration: none;
  }
  .navbar:link{
    text-decoration: none;
  }
  .textHeader {
    height: 100%;
    display: flex;
    flex-direction: column;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.5);
  }
  .prenom {
    border-collapse: collapse;
    border: 1px solid white;
    margin: auto;
    margin-top: 60px;
    padding: 3%;
    background-color: rgba(0, 0, 0, 0.8);
  }
  .infos {
    border-collapse: collapse;
    border: 1px solid white;
    margin: auto;
    width: 500px;
    padding: 3%;
    background-color: rgba(0, 0, 0, 0.8);
    text-align: justify;
  }

  html{
    height: 3000px;
    background-color: #52474a;
  }
  nav {
    display: flex;
    height: 50px;
    align-items: center;

  }
  a {
    text-decoration: none;
    color: white;

  }
</style>

<script>
  // @ is an alias to /src
  import Swal from 'sweetalert2/dist/sweetalert2.js';
  import 'sweetalert2/src/sweetalert2.scss'


  export default {
    name: 'Home',
    beforeMount() {
      Swal.fire('Site web actuellement en construction')
    }
  }
</script>
