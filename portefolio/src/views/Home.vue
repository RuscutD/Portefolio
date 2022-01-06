<template>
  <div class="home">
    <div class="top">
      <div class="topLeft">
        <img alt="Vue logo" src="../assets/img/profilePicture.jpeg" class="profilePicutre">
          <h1 class="name">Ruscuta David</h1>
        <h3>Étudiant Développement Web</h3>
        <div class="etna-space">
          <img alt="Etna logo" src="../assets/img/etna.png" class="EtnaPicture">
        </div>
      </div>
      <div class="topMiddle">
      </div>
      <div class="topRight">
        <h1><em>"Il semble que la perfection soit atteinte non quand il n’y a plus rien à ajouter, mais quand il n’y a plus rien à retrancher."</em></h1>
        <h3>Antoine de Saint-Exupéry</h3>
      </div>
    </div>
    <div id="mainDiv">
        <div id="boxDiv">
            <div id="front"></div>
            <div id="back"></div>
            <div id="left"></div>
            <div id="right"></div>
            <div id="top"></div>
            <div id="bottom"></div>
            <div class="shadow"></div>
        </div>
    </div>    
    <div class="bottom">
      <h1 class="comp-txt">Maîtrise des differents languages</h1>
      <div class="line"></div>
      <div class="competences">
        <div id="btn-html" class="comp">
          <h4 class="html">HTML 5</h4>
          <hr class="html-hr">
          <img src="../assets/img/html.png" alt="html logo" class="logo">
            <div class="comp-cont">
              <p class="p-html">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Obcaecati et exercitationem aperiam, repellat similique enim quasi fugit laboriosam laborum architecto, rem illum veniam. Debitis officiis harum doloribus iusto soluta aspernatur.</p>
            </div>
              <progress class="html-lvl" max="100" value="50"></progress>
        </div>
        <div id="btn-css" class="comp">
          <h4>CSS 3</h4>
          <hr class="css-hr">
          <img src="../assets/img/css.png" alt="css logo" class="logo">
            <div class="comp-cont">
              <p class="p-css">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Obcaecati unde nemo perferendis debitis sequi explicabo porro aliquam quis officiis impedit in temporibus, distinctio id provident repudiandae sed veniam placeat. Vero.</p>
            </div>
              <progress class="css-lvl" max="100" value="50"></progress>
        </div>
        <div id="btn-js" class="comp">
          <h4>JAVASCRIPT</h4>
          <hr class="js-hr">
          <img src="../assets/img/js.png" alt="js logo" class="logo">
            <div class="comp-cont">
              <p class="p-js">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem sint, quas possimus ipsa non cupiditate eum maiores dicta ex sequi error, necessitatibus repellat praesentium! Eius iure quam accusamus quaerat placeat.</p>
            </div>
              <progress class="js-lvl" max="100" value="30"></progress>
        </div>
        <div id="btn-php" class="comp">
          <h4>PHP</h4>
          <hr class="php-hr">
          <img src="../assets/img/php.png" alt="php logo" class="logo">
            <div class="comp-cont">
              <p class="p-php">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Expedita quibusdam maxime quis quisquam quaerat, dolore repellendus et? Dolores, repellendus minima. Earum rerum, eius excepturi reprehenderit perspiciatis quod molestias nihil voluptate?</p>
            </div>
              <progress class="php-lvl" max="100" value="10"></progress>
        </div>
        <div id="btn-sql" class="comp">
          <h4>SQL</h4>
          <hr class="sql-hr">
          <img src="../assets/img/sql.png" alt="sql logo" class="logo">
            <div class="comp-cont">
              <p class="p-sql">Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita alias odio consectetur enim amet, ratione quod consequatur, autem non voluptates repudiandae provident officia dolor ab quisquam blanditiis placeat! Iure, dolorum.</p>
            </div>
              <progress class="sql-lvl" max="100" value="50"></progress>
        </div>
      </div>
    </div>
  </div>
</template>