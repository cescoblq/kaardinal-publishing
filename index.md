---
title: Accueil — Kaardinal Publishing
---

<!-- STYLES MODERNES -->
<style>
  body {
    font-family: 'Segoe UI', 'Helvetica Neue', sans-serif;
    max-width: 960px;
    margin: 0 auto;
    padding: 2em;
    color: #222;
    background-color: #fdfdfd;
  }

  h1, h2, h3 {
    text-align: center;
    margin-top: 1.5em;
  }

  p, a {
    text-align: center;
    font-size: 1.1em;
  }

  a {
    color: #0077cc;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  .gallery {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    justify-content: center;
    margin: 2em auto;
  }

  .gallery img {
    width: 400px;
    height: 400px;
    object-fit: cover;
    display: block;
    margin: auto;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  }

  .gallery-partners {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
    align-items: center;
    justify-items: center;
    margin: 2em auto;
  }

  .gallery-partners img {
    max-width: 160px;
    height: auto;
    object-fit: contain;
    filter: grayscale(100%);
    opacity: 0.8;
    transition: 0.3s;
  }

  .gallery-partners img:hover {
    filter: none;
    opacity: 1;
  }

  form {
    max-width: 600px;
    margin: 3em auto;
    background: #fff;
    padding: 2em;
    border-radius: 10px;
    box-shadow: 0 4px 14px rgba(0, 0, 0, 0.05);
  }

  form input,
  form textarea {
    width: 100%;
    padding: 1em;
    margin-bottom: 1em;
    border: 1px solid #ccc;
    border-radius: 6px;
    font-size: 1em;
  }

  form button {
    background-color: #0077cc;
    color: white;
    padding: 1em 2em;
    border: none;
    border-radius: 6px;
    font-size: 1em;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  form button:hover {
    background-color: #005fa3;
  }
</style>

<!-- Logo -->
<p style="text-align:center;">
  <img src="assets/logo.png" alt="Kaardinal Publishing" style="max-width:200px;">
</p>

# Kaardinal Publishing

**Independent Music Publisher — France**  
*Éditeur de musique indépendant — France*

<p>
  <a href="about.md">About</a> |
  <a href="contacts.md">Contacts</a>
</p>

<!-- Galerie Artistes -->
<div class="gallery">
  <a href="artist1.md"><img src="assets/images/ablaye-cissoko.jpg" alt="Ablaye Cissoko"></a>
  <a href="artist2.md"><img src="assets/images/moonlight-benjamin.jpg" alt="Moonlight Benjamin"></a>
  <a href="artist3.md"><img src="assets/images/selin-sumbultepe.jpg" alt="Selin Sümbültepe"></a>
  <a href="artist4.md"><img src="assets/images/cyrille-brotto.jpg" alt="Cyrille Brotto"></a>
  <a href="artist5.md"><img src="assets/images/lorke-lorke.jpg" alt="Lorkê Lorkê"></a>
  <a href="artist6.md"><img src="assets/images/vide.jpg" alt="Bientôt disponible"></a>
</div>

<!-- Galerie Partenaires -->
<h2>Partners (publishing / booking)</h2>

<div class="gallery-partners">
  <a href="#"><img src="assets/images/logo-musigamy.png" alt="Musigamy"></a>
  <a href="#"><img src="assets/images/logo-absilone.png" alt="Absilone"></a>
  <a href="#"><img src="assets/images/logo-ma-case.png" alt="Ma Case Prod"></a>
</div>

<!-- Formulaire de contact -->
<h2>Contact Us</h2>

<form action="https://formsubmit.co/contact@kaardinal-publishing.com" method="POST">
  <input type="hidden" name="_captcha" value="false">
  <input type="email" name="email" placeholder="Your email" required>
  <input type="text" name="firstname" placeholder="First name" required>
  <input type="text" name="lastname" placeholder="Last name" required>
  <input type="text" name="subject" placeholder="Subject" required>
  <textarea name="message" placeholder="Your message..." rows="6" required></textarea>
  <button type="submit">Send</button>
</form>
