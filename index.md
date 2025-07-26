---
title: Accueil — Kaardinal Publishing
---

<style>

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  html, body {
    height: 100%;
  }

 header, h1.title, .site-title {
  display: none !important;  /*pour effacer le titre rajouté par Jekyl et Yaml */
 }

 
  body {
    margin: 0;
    padding: 0;
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

  hr {
    border: none;
    border-top: 2px solid #eee;
    margin: 3em 0;
  }

  .gallery {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 40px;
    justify-content: center;
    margin: 2em auto;
  }

  .gallery-item {
    text-align: center;
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

  .gallery .caption {
    margin-top: 0.5em;
    font-weight: 500;
    font-size: 1.1em;
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


  footer {
    background-color: #111;
    color: #fff;
    padding: 2em 1em;
    margin-top: 4em;
    width: 100vw;
    position: relative;
    left: 50%;
    right: 50%;
    margin-left: -50vw;
    margin-right: -50vw;
  }


  .footer-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
    max-width: 960px;
    margin: 0 auto;
  }

  .footer-logo img {
    max-width: 150px;
    height: auto;
  }

  .footer-info {
    font-size: 0.9em;
    line-height: 1.4em;
    text-align: right;
  }

  .social-links {
    margin-top: 0.5em;
    display: flex;
    justify-content: center;
    gap: 12px;
  }
  
  .social-links img {
    width: 24px;
    height: 24px;
    opacity: 0.7;
    transition: 0.2s;
  }
  
  .social-links img:hover {
    opacity: 1;
    transform: scale(1.1);
  }

  .artist-description {
    margin-top: 1.2em;        /* ↑ plus d'espace avec les logos */
    font-size: 0.95em;
    color: #444;
    line-height: 1.5;
    padding: 0 1em;
    text-align: justify;      /* ← texte justifié */
  }



  @media(max-width: 600px) {
    .gallery {
      grid-template-columns: 1fr;
    }
    .footer-container {
      flex-direction: column;
      gap: 1em;
      text-align: center;
    }
    .footer-info {
      text-align: center;
    }
  }
</style>

<!-- Logo -->
<p style="text-align:center;">
  <img src="assets/images/logo-kaardinal-web-black-transparent.png" alt="Kaardinal Publishing Logo" style="max-width:200px;">
</p>

# Kaardinal Publishing

**Independent Music Publisher — France**  
*Éditeur de musique indépendant — France*

<p>
  <a href="about.md">About</a> |
  <a href="contacts.md">Contacts</a>
</p>

---

## 🎵 Our Artists

<div class="gallery">
  <div class="gallery-item">
    <a href="artist1.md"><img src="assets/images/ablaye-cissoko.jpg" alt="Ablaye Cissoko"></a>
    <div class="caption">Ablaye Cissoko</div>
    <div class="social-links">
      <a href="https://instagram.com/ablayecissoko" target="_blank"><img src="https://cdn.simpleicons.org/instagram/000000" alt="Instagram"></a>
      <a href="https://open.spotify.com/artist/xxxxx" target="_blank"><img src="https://cdn.simpleicons.org/spotify/000000" alt="Spotify"></a>
      <a href="https://youtube.com/channel/xxxxx" target="_blank"><img src="https://cdn.simpleicons.org/youtube/000000" alt="YouTube"></a>
      <a href="https://facebook.com/ablayecissoko" target="_blank"><img src="https://cdn.simpleicons.org/facebook/000000" alt="Facebook"></a>
    </div>
    <div class="artist-description">
      Master of the kora and one of the purest West African voice, Ablaye Cissoko blends Senegalese tradition with modern elegance in a deeply poetic and spiritual sound.  1M monthly streams, and wordlwide sold-out tours every year?
    </div>   
  </div>
  
  <div class="gallery-item">
    <a href="artist2.md"><img src="assets/images/moonlight-benjamin.jpg" alt="Moonlight Benjamin"></a>
    <div class="caption">Moonlight Benjamin</div>
   <div class="social-links">
      <a href="https://instagram.com/ablayecissoko" target="_blank"><img src="https://cdn.simpleicons.org/instagram/000000" alt="Instagram"></a>
      <a href="https://open.spotify.com/artist/xxxxx" target="_blank"><img src="https://cdn.simpleicons.org/spotify/000000" alt="Spotify"></a>
      <a href="https://youtube.com/channel/xxxxx" target="_blank"><img src="https://cdn.simpleicons.org/youtube/000000" alt="YouTube"></a>
      <a href="https://facebook.com/ablayecissoko" target="_blank"><img src="https://cdn.simpleicons.org/facebook/000000" alt="Facebook"></a>
    </div>
     <div class="artist-description">
Vodou Garage / The Punky Voodoo Queen / The Caribbean Patti Smith | Rebellious Caribbean garage blues-rock from Haitian voodoo priestess | A primal scream, a mystifying and mystical musical mixture, almost shamanic, an incantation of liberation in the midst of raging guitars and propulsive drumming.</div>   
  </div>
  
  <div class="gallery-item">
    <a href="artist3.md"><img src="assets/images/selin-sumbultepe.jpg" alt="Selin Sümbültepe"></a>
    <div class="caption">Selin Sümbültepe</div>
    <div class="social-links">
      <a href="https://instagram.com/ablayecissoko" target="_blank"><img src="https://cdn.simpleicons.org/instagram/000000" alt="Instagram"></a>
      <a href="https://open.spotify.com/artist/xxxxx" target="_blank"><img src="https://cdn.simpleicons.org/spotify/000000" alt="Spotify"></a>
      <a href="https://youtube.com/channel/xxxxx" target="_blank"><img src="https://cdn.simpleicons.org/youtube/000000" alt="YouTube"></a>
      <a href="https://facebook.com/ablayecissoko" target="_blank"><img src="https://cdn.simpleicons.org/facebook/000000" alt="Facebook"></a>
    </div>
    <div class="artist-description">
Somewhere between Altın Gün, Acid Arab, and Omar Souleyman, Lorkê Lorkê’s compositions take us on a retro-futuristic whirlwind, oscillating between Middle Eastern traditions and electric grooves.    </div>   
  </div>
  
  <div class="gallery-item">
    <a href="artist4.md"><img src="assets/images/cyrille-brotto.jpg" alt="Cyrille Brotto"></a>
    <div class="caption">Cyrille Brotto</div>
    <div class="social-links">
      <a href="https://instagram.com/ablayecissoko" target="_blank"><img src="https://cdn.simpleicons.org/instagram/000000" alt="Instagram"></a>
      <a href="https://open.spotify.com/artist/xxxxx" target="_blank"><img src="https://cdn.simpleicons.org/spotify/000000" alt="Spotify"></a>
      <a href="https://youtube.com/channel/xxxxx" target="_blank"><img src="https://cdn.simpleicons.org/youtube/000000" alt="YouTube"></a>
      <a href="https://facebook.com/ablayecissoko" target="_blank"><img src="https://cdn.simpleicons.org/facebook/000000" alt="Facebook"></a>
    </div>
     <div class="artist-description">
One of the top3 diatonic accordion master players in Europe, blending tradition and modern tune.     </div>   
  </div>
  
  <div class="gallery-item">
    <a href="artist5.md"><img src="assets/images/lorke-lorke.jpg" alt="Lorkê Lorkê"></a>
    <div class="caption">Lorkê Lorkê</div>
    <div class="social-links">
      <a href="https://instagram.com/ablayecissoko" target="_blank"><img src="https://cdn.simpleicons.org/instagram/000000" alt="Instagram"></a>
      <a href="https://open.spotify.com/artist/xxxxx" target="_blank"><img src="https://cdn.simpleicons.org/spotify/000000" alt="Spotify"></a>
      <a href="https://youtube.com/channel/xxxxx" target="_blank"><img src="https://cdn.simpleicons.org/youtube/000000" alt="YouTube"></a>
      <a href="https://facebook.com/ablayecissoko" target="_blank"><img src="https://cdn.simpleicons.org/facebook/000000" alt="Facebook"></a>
    </div>
    <div class="artist-description">
Somewhere between Altın Gün, Acid Arab, and Omar Souleyman, Lorkê Lorkê’s compositions take us on a retro-futuristic whirlwind, oscillating between Middle Eastern traditions and electric grooves.    </div>   
  </div>
  
  <!--<div class="gallery-item">
    <a href="artist6.md"><img src="assets/images/vide.jpg" alt=""></a>
    <div class="caption">À venir</div>  
  </div>-->
</div>

---

## 🤝 Partners (Publishing / Booking)

<div class="gallery-partners">
  <a href="#"><img src="assets/images/logo-musigamy.png" alt="Musigamy"></a>
  <a href="#"><img src="assets/images/logo-absilone.png" alt="Absilone"></a>
  <a href="#"><img src="assets/images/logo-ma-case.png" alt="Ma Case Prod"></a>
</div>

---

## 📬 Contact Us

<form action="https://formsubmit.co/contact@kaardinal-publishing.com" method="POST">
  <input type="hidden" name="_captcha" value="false">
  <input type="email" name="email" placeholder="Your email" required>
  <input type="text" name="firstname" placeholder="First name" required>
  <input type="text" name="lastname" placeholder="Last name" required>
  <input type="text" name="subject" placeholder="Subject" required>
  <textarea name="message" placeholder="Your message..." rows="6" required></textarea>
  <button type="submit">Send</button>
</form>

<footer>
  <div class="footer-container">
    <div class="footer-logo">
      <img src="assets/images/logo-kaardinal-web-footer.jpg" alt="Kaardinal Publishing logo">
    </div>
    <div class="footer-info">
      <strong>SASU Kaardinal Publishing</strong><br>
      60 rue François 1er - 75008 Paris - France<br>
      SIREN : 944682137
    </div>
  </div>
</footer>
