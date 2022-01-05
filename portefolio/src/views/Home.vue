<template>
  <div class="home">
    <div class="top">
      <img alt="Vue logo" src="../assets/img/profilePicture.jpeg" class="profilePicutre">
      <div class="name">
        <HelloWorld msg="Ruscuta David"/>
      </div>
      <h3>Étudiant Développement Web</h3>
      <div class="etna-space">
        <img alt="Etna logo" src="../assets/img/etna.png" class="EtnaPicture">
      </div>
    </div>
    <div class="bottom">
      <div class="competences">
        <div id="btn-html" class="comp">
          <h4 class="html">HTML 5</h4>
          <img src="../assets/img/html.png" alt="html logo" class="logo">
            <div class="p-html">
              <p>Maitrise HTML</p>
            </div>
        </div>
        <div id="btn-css" class="comp">
          <h4>CSS 3</h4>
          <img src="../assets/img/css.png" alt="css logo" class="logo">
            <div>
              <p class="p-css">Maitrise CSS</p>
            </div>
        </div>
        <div id="btn-js" class="comp">
          <h4>JAVASCRIPT</h4>
          <img src="../assets/img/js.png" alt="js logo" class="logo">
            <div>
              <p class="p-js">Maitrise JAVASCRIPT</p>
            </div>
        </div>
        <div id="btn-php" class="comp">
          <h4>PHP</h4>
          <img src="../assets/img/php.png" alt="php logo" class="logo">
            <div>
              <p class="p-php">Maitrise PHP</p>
            </div>
        </div>
        <div id="btn-sql" class="comp">
          <h4>SQL</h4>
          <img src="../assets/img/sql.png" alt="sql logo" class="logo">
            <div>
              <p class="p-sql">Maitrise SQL</p>
            </div>
        </div>
        <div id="btn-laravel" class="comp">
          <h4>Laravel</h4>
          <img src="../assets/img/laravel.png" alt="laravel logo" class="logo">
            <div>
              <p class="p-laravel">Maitrise Laravel</p>
            </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped lang="scss">
.home {
  margin: 0;
  display:flex;
  flex-direction: column ;
  justify-content: space-around;
}

.top {
  height: 600px;
  width: 500px;

  margin-left: 100px;
}

.bottom {
  height: 600px;
  width: 700px;

  margin: 0 auto;
  margin-top: 200px;
  padding: 2%;

  border: solid red;
}

.profilePicutre {
  height: 400px;
  widows: auto;
  margin-bottom: 60px;
}

.EtnaPicture {
  width: 100px;
  height: auto;
}

.etna-space {
  padding-top: 3px;
  padding-left: 20px;
  background-color: white;
  width: 130px;
  height: 35px;
}

.logo {
  height: 100px;
  width: 100px;
}

.name {
  color: white;
  font-size: 20px;
}

h3 {
  color: white;
  font-size: 20px;
}

.competences {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}

.comp {
  width: 250px;
  height: 150px;
  padding: 10px;

  display: flex;
  flex-wrap: wrap;
  flex-direction: column;

  background-color: rgb(179, 179, 179);
  box-shadow: 0px 5px 5px 2px rgba(0, 0, 0, 0.371);
  border-radius: 10px;
  cursor: pointer;
}

.comp:hover {
  transition-duration: 0.5s;
  background-color: rgb(128, 128, 128);
  box-shadow: 0px 5px 5px 5px rgba(150, 150, 150, 0.522);
  width: 270px;
  height: 170px;
}

.p-html {
  width: 100px;
  height: 50px;

  display: none;
  background-color: red($color: #4b0d0d);
}

#btn-html:hover .p-html {
  color: red;
  display: block;
}

.p-css {
  width: 100px;
  height: 50px;

  display: none;
  background-color: red($color: #4b0d0d);
}

#btn-css:hover .p-css {
  color: red;
  display: block;
}

.p-js {
  width: 100px;
  height: 50px;

  display: none;
  background-color: red($color: #4b0d0d);
}

#btn-js:hover .p-js {
  color: red;
  display: block;
}

.p-php {
  width: 100px;
  height: 50px;

  display: none;
  background-color: red($color: #4b0d0d);
}

#btn-php:hover .p-php {
  color: red;
  display: block;
}

.p-sql {
  width: 100px;
  height: 50px;

  display: none;
  background-color: red($color: #4b0d0d);
}

#btn-sql:hover .p-sql {
  color: red;
  display: block;
}

.p-laravel {
  width: 100px;
  height: 50px;

  display: none;
  background-color: red($color: #4b0d0d);
}

#btn-laravel:hover .laravel {
  color: red;
  display: block;
}

</style>

