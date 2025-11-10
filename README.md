<!DOCTYPE html>
<html lang="en">
<style>
  body {
    text-align: center;
    background: linear-gradient(#0000FF, #FF0000 ) ;
  }
</style>
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FC Barcelona | Official Fan Page</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <style>
     .container{
            width: 100%;
            height: auto;
            display: grid;
            grid-template-rows: auto auto auto auto;
        }
        .head{
            margin-left: 1%;
            margin-right: 1%;
            margin-top: 1%;
            display: grid;
            grid-template-columns: auto auto;
            background-color: black;
        }
        .navbar ul{
            list-style-type: none;
            overflow: hidden;
            margin: 0;
            padding: 0;
        }
        .navbar ul li{
            float: right;
        }
        .navbar ul li a{
            display:block;
            text-align: center;
            text-decoration: none;
            font-size: 20px;
            padding: 25px 15px;
            color: grey;
        }
        .navbar ul li a:hover{
            color: black;
            background-color: grey;
        }
    </style>
    <head></head>
    <body>
        <div class = "container">
            <div class = "head">
                <div class = "logo">  <img src="https://upload.wikimedia.org/wikipedia/en/4/47/FC_Barcelona_%28crest%29.svg" alt="FC Barcelona Logo" class="logo" width="70" height="auto" />;"></div>
                <div class = "navbar">
                    <ul>
                    
        <li><a href="#players" width="auto" height="auto" >Players</a></li>
         <li><a href="#home" width="auto" height="auto" >Home</a></li>
                
                    </ul>
                </div>
            </div>
            <div class = "slide">
  </header>

  <section id="home" class="hero">
    <h2>More Than a Club — Més que un club</h2>
    <p>Welcome to the FC Barcelona fan page. Stay up to date with the latest news, players, and highlights.</p>
    <button onclick="alert('Visca el Barça!')">Cheer for Barça</button>
  </section>

  <section id="players">
    <h2>Star Players</h2>
    <div class="player-grid">
      <div class="player">
        <h3>Robert Lewandowski</h3>
        <p>Forward — Poland</p>
      <img src="mini__GP12285.webp" width="300" height="auto">
      </div>
      <div class="player">
        <h3>Pedri</h3>
        <p>Midfielder — Spain</p>
        <img src="image.jpg" width="300" height="auto">
      </div>
      <div class="player">
        <h3>Raphinha</h3>
        <p>Winger — Brazil</p>
        <img src="fc-barcelona-v-fc-bayern-munchen-uefa-champions-league-2024-25-league-phase-md3-1.jpg" width="300" height="auto">
        <div class="player">
        <h3>Yamal</h3>
        <p>Winger — Spain</p>
        <img src="Lamine Yamal celebrates after scoring agisnts Real Madrid.jpg" width="300" height="auto">
      </div>
    </div>
  </section>

  <section id="history">
    <h2>Club History</h2>
    <p>Founded in 1899 by a group of Swiss, Catalan, German, and English footballers led by Joan Gamper, FC Barcelona has grown to become one of the world’s most successful football clubs, with a philosophy rooted in community, excellence, and Catalan pride.</p>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery-grid">
      <img src="WOO-architects-Camp-Nou-Stadium-Barcelona.png" width="300" height="auto">
      <img src="tickets-for-fcbarcelona-t24c.jpg" width="300" height="auto">
    </div>
  </section>
  <script src="script.js"></script>

</body>
</html>
