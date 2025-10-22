<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>RSLIFE — Coaching & Réconciliation</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="site-header">
    <div class="container">
      <div class="brand">
        <h1>RSLIFE</h1>
        <p class="tag">Projet de réconciliation</p>
      </div>
      <nav class="main-nav">
        <a href="#home">Accueil</a>
        <a href="#services">Services</a>
        <a href="#about">À propos</a>
        <a href="#contact">Contact</a>
      </nav>
      <button id="navToggle" class="nav-toggle" aria-label="menu">☰</button>
    </div>
  </header>

  <main>
    <section id="home" class="hero">
      <div class="container hero-grid">
        <div class="hero-text">
          <h2>Sofia JTM</h2>
          <p class="lead">Coaching amour et bien-être</p>
          <p class="intro">Projet de réconciliation — un espace pour écouter, comprendre et rapprocher les cœurs.</p>
          <a class="btn" href="#contact">Parler maintenant</a>
        </div>

        <div class="hero-image">
          <!-- Place ton image dans /images/sofia.jpg -->
          <img src="images/sofia.jpg" alt="Photo RSLIFE" />
        </div>
      </div>
    </section>

    <section id="services" class="section">
      <div class="container">
        <h3>Services</h3>
        <div class="grid">
          <article class="card">
            <h4>Coaching amour</h4>
            <p>Soutien personnalisé pour renouer le dialogue et renforcer la relation.</p>
          </article>
          <article class="card">
            <h4>Bien-être émotionnel</h4>
            <p>Ateliers et exercices pour retrouver sérénité et clarté émotionnelle.</p>
          </article>
          <article class="card">
            <h4>Projet de réconciliation</h4>
            <p>Accompagnement pas à pas pour créer des occasions de communication vraie.</p>
          </article>
        </div>
      </div>
    </section>

    <section id="about" class="section alt">
      <div class="container">
        <h3>À propos</h3>
        <p>RSLIFE est un projet dédié au coaching affectif et au bien-être, conçu pour aider les personnes et les couples à se reconnecter. Approche empathique, techniques simples et exercices pratiques pour améliorer l’écoute et la communication.</p>
      </div>
    </section>

    <section id="contact" class="section">
      <div class="container">
        <h3>Contact</h3>
        <div class="contact-grid">
          <form id="contactForm" class="contact-form">
            <label>Nom<input type="text" name="name" required></label>
            <label>Email<input type="email" name="email" required></label>
            <label>Message<textarea name="message" rows="5" required></textarea></label>
            <button class="btn" type="submit">Envoyer</button>
          </form>

          <div class="contact-info">
            <p><strong>Instagram :</strong> <a href="https://instagram.com/r3dvrs" target="_blank" rel="noopener">@r3dvrs</a></p>
            <p><strong>But du site :</strong> Je voudrais un site pour que ma femme m’écoute.</p>
            <p class="small">Tu peux remplacer le formulaire par un email direct si tu préfères — change l'action dans le fichier HTML.</p>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year"></span> RSLIFE — Coaching & réconciliation</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
