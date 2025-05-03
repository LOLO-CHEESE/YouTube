<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>YouTube</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
</head>
<body>
  <header>
    <div class="logo">YouTube</div>
    <div class="search-bar">
      <input type="text" placeholder="Rechercher">
      <button><span class="material-icons">search</span></button>
    </div>
  </header>

  <main>
    <aside>
      <nav>
        <ul>
          <li><span class="material-icons">home</span> Accueil</li>
          <li><span class="material-icons">whatshot</span> Tendances</li>
          <li><span class="material-icons">subscriptions</span> Abonnements</li>
        </ul>
      </nav>
    </aside>

    <section class="videos">
      <a href="video.html?video=video1.mp4" class="video-card">
        <img src="thumb1.jpg" alt="Vidéo 1">
        <h3>Vidéo 1</h3>
        <p>Chaîne 1</p>
      </a>
      <a href="video.html?video=video2.mp4" class="video-card">
        <img src="thumb2.jpg" alt="Vidéo 2">
        <h3>Vidéo 2</h3>
        <p>Chaîne 2</p>
      </a>
    </section>
  </main>
</body>
</html>
