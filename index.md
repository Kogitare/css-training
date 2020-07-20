<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="logo icon" href="images/icon.png" />
    <link rel="stylesheet" href="reset.css" />
    <link rel="stylesheet" href="style.css" />
    <title>CSS Training!</title>
  </head>
  <body>
    <header class="header">
      <a href="#contacts" class="btn btn--contact">Contact</a>
      <a href="#things" class="btn btn--things">Things</a>
      <a href="#main" class="btn btn--main">Main</a>
    </header>

    <div id="main">
      <h1 class="main-head">It's CSS Training!</h1>
      <h2 class="main-caption">very cool</h2>
    </div>

    <div id="things">
      <h1 class="things-title">These are things I made :)</h1>
      <div class="things-windows">
        <div class="things-window things-window--poster1">
          <img class="things-window__img" src="images/icon.png" alt="" />
          <p class="things-window__p">Poster 1</p>
        </div>
        <div class="things-window things-window--poster2">
          <img src="images/icon.png" alt="" />
          <p>Poster 2</p>
        </div>
        <div class="things-window things-window--blender">
          <img src="images/icon.png" alt="" />
          <p>3D model of Portal 2 cube</p>
        </div>
        <div class="things-window things-window--gol">
          <img src="images/icon.png" alt="" />
          <p>Game of Life</p>
        </div>
      </div>
    </div>

    <div id="contacts">
      <h1 class="contacts-head">These are my socials...</h1>
      <h2 class="contacts-caption">If you really want to contact me</h2>
      <div class="contacts-content">
        <p class="contact contact--github">Github</p>
        <p class="contact contact--mail">E-mail</p>
        <p class="contact contact--tel">Phone</p>
      </div>
      <div class="end-info">
        <p class="end-info-statement">
          This page was created for learning purposes.
        </p>
        <a class="made-by" href="https://kogitare.github.io/">
          <img
            class="made-by__logo"
            src="images/icon.png"
            alt="Creator's logo"
          />
          <p class="made-by__p">Made by Kogitare</p>
        </a>
      </div>
    </div>
  </body>
</html>
