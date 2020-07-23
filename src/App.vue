<template>
    <div class="header">
        <div class="textHeader">
            <nav class="navbar navbar-expand-sm navbar-dark">
                <div  class="mx-auto d-sm-flex d-block flex-sm-nowrap">
                    <button class="navbar-toggler d-flex float-left" type="button" data-toggle="collapse" data-target="#navbarsExample11" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>

                    <div class="collapse navbar-collapse" id="navbarsExample11">
                        <div class="text-center">
                            <ul class="navbar-nav">
                                <li class="nav-item active">
                                    <router-link class="nav-link" to="/">Accueil</router-link>
                                </li>
                                <li class="nav-item">
                                    <router-link class="nav-link" to="/enfants">Enfants</router-link>
                                </li>
                                <li class="nav-item">
                                    <router-link class="nav-link" to="/adolescentes">Adolescentes</router-link>
                                </li>
                                <li class="nav-item">
                                    <router-link class="nav-link" to="/femmes">Femmes</router-link>
                                </li>
                                <li class="nav-item">
                                    <router-link class="nav-link" to="/hommes">Hommes</router-link>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </nav>
            <router-view/>
        </div>
    </div>

</template>

<style lang="scss">
    html, body {
        margin: 0;
        padding: 0;
    }

    .header {
        height: 1000px;
        display: block;
        background-image: url(assets/images/fond2.jpg);
        background-size: cover;
        background-attachment: fixed;
        color: white;
    }

    .navbar {
        display: flex;
        color: white;
        text-decoration: none;
    }

    .navbar:link {
        text-decoration: none;
    }

    .textHeader {
        height: 100%;
        display: flex;
        flex-direction: column;
        width: 100%;
        background-color: rgba(0, 0, 0, 0.6);
    }

    .prenom {
        border-collapse: collapse;
        border: 1px solid white;
        margin: auto;
        margin-top: 60px;
        margin-bottom: 50px;
        width: 400px;
        padding: 3%;
        background-color: rgba(0, 0, 0, 0.8);
    }

    html {
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
