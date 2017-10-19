<template lang="pug">
#app
  .container.text_mariachi
    .row
      .col-lg-6.col-12
        img#logo_mariachi(src='dist/logo_mariachi.png', alt='logo')
        h1 Nos estamos renovando
        h2 Llevaremos tus ideas al siguiente nivel,
        p
          | utilizando las tecnologías de desarrollo más novedosas podremos diseñarte una solucion adecuada.
      .col-lg-6.col-12
        .row.logos
          .col-sm-12
            h3 Nuestros clientes
            .row
              .col-lg-4.col-12
                img(src='dist/allianz_logo.png', alt='logo')
              .col-lg-4.col-12
                img(src='dist/gsalinas_logo.png', alt='logo')
              .col-lg-4.col-12
                img(src='dist/traveo_logo.png', alt='logo')
          .col-sm-12
            h3 Partnership
            .row
              .col-lg-3.col-12
              .col-lg-6.col-12
                img(src='dist/oraclep_logo.png', alt='logo')
                //- img(src='dist/oracle_logo.png', alt='logo')
              .col-lg-3.col-12
  footer
    h6#derechos © Derechos reservados 2017
    h6#correo hola@mariachi.io
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Exo:300,900|Montserrat');
#app {
  font-family: 'Exo', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 60px;
}

body {
    background-image: url("https://joseangelchepo.github.io/mariachi-page/dist/Background_image.png");
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
.text_mariachi {
  max-width: 95%;
  margin-top: 5%;
  text-align: left;
}
#logo_mariachi {
    margin-top: 20px;
    margin-bottom: 20px;
}
.text_mariachi h1{
  font-weight: 300;
  font-size: 60px;
}
.text_mariachi h2{
  font-weight: 900;
  font-size: 24px;
}
.text_mariachi h3{
  font-weight: 900;
  font-size: 24px;
  margin-top: 20px;
  margin-bottom: 20px;
  color: #45D9E1;
  text-align: center;
}
.text_mariachi p{
  font-weight: 300;
  font-size: 26px;
}
.logos img {
  max-width: 100%;
  display: block;
  margin: auto;
}
footer {
  background-color: #101F2D;
  color: #516980;
  text-align: center;
  bottom: 0;
  position:fixed;
  width: 100%;
}
footer h6 {
  margin-top: 20px;
  margin-bottom: 20px;
  font-family: 'Montserrat';
  font-size: 12px;
  display: inline-block;
}
#derechos{
  text-align: center;
}
#correo {
  float: right;
  margin-right: 10px;
}
</style>
