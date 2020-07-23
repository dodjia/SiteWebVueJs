<template>
    <div>
        <div class="prenom">
            <p class="d-flex justify-content-center">Estelle Lesein </p>
            <p class="d-flex justify-content-center profession">Psychologue clinicienne</p>
        </div>
        <div class="infos d-flex justify-content-center">
            <img class="profilImage" src="../assets/images/pp.jpg" alt="photo">
            <div class="infoText">
                <div class="quisuisje">
                    Qui suis-je ?
                </div>
                La psychologie et le développement personnel est un choix de vie pour moi. Après un parcours
                professionnel dans de multiples domaines,
                j’ai choisi de reprendre mes études à l’âge de 34 ans par vocation. L’humain est pour moi une véritable
                source d’inspiration et ma passion est de l’accompagner autant qu’il m’est possible,
                vers la prise de conscience de ses potentiels et de ses multiples possibilités.
            </div>
        </div>
        <div class="prenom d-flex justify-content-center contact">
            <div class="infoText">
                <div>
                    Me contacter:
                </div>
                <div class="marginTopPrenom">
                    Vous pouvez me contacter par téléphone au: 07 86 57 79 45
                </div>
                <div class="marginTopPrenom">
                    Par mail: EstelleLesein@gmail.com
                </div>
                <div class="marginTopPrenom">
                    Ou :
                </div>
                <div class="d-flex justify-content-center">

                    <div class="rdvButton justify-content-center">
                        <div  class="marginauto  d-flex justify-content-center">
                            <a class="link" href="https://www.doctolib.fr/psychologue/rixheim/estelle-lesein-ulmann"
                               target="_blank"> Prendre rendez-vous directement en ligne </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss">
    .marginTopPrenom {
        margin-top: 20px;
    }

    .profilImage {
        width: 1250px;
        float: left;
    }

    .quisuisje {
        margin-bottom: 6px;
    }

    .infos {
        border-collapse: collapse;
        border: 1px solid white;
        margin: auto;
        width: 800px;
        background-color: rgba(0, 0, 0, 0.8);
        text-align: justify;
        vertical-align: middle;
        display: inline-block;
        margin-bottom: 20px;
    }

    .infoText {
        padding: 3%;
        padding-left: 20px;

    }

    .link {
        text-decoration: none;
    }

    .rdvButton {
        margin-top: 35px;
        background-color: rgba(61, 52, 52, 0.92);
        width: 200px;
        text-decoration: none;
        transition: 0.3s;

    }
    .rdvButton:hover {
        margin-top: 35px;
        background-color: rgba(137, 117, 117, 0.92);
        width: 200px;
        text-decoration: none;

    }
    .link:hover {
        text-decoration: none;
        color: white;
    }
    .marginauto {
        margin: auto;
    }
</style>

<script>
    // @ is an alias to /src
    import 'sweetalert2/src/sweetalert2.scss'


    export default {
        name: 'Home',
    }
</script>
