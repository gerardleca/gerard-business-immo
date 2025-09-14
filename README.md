<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gérard Business Services</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f8f9fa;
      color: #333;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 40px;
      background: #004080;
      color: white;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header img {
      height: 60px;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      background: url("images/immobilier.jpg") center/cover no-repeat;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
    }
    .hero h1 {
      font-size: 2.5rem;
      background: rgba(0,0,0,0.5);
      padding: 20px;
      border-radius: 10px;
    }
    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }
    h2 {
      color: #004080;
      margin-bottom: 20px;
      text-align: center;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }
    .service {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      overflow: hidden;
    }
    .service img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .service p {
      padding: 15px;
    }
    .contact p {
      margin: 10px 0;
      text-align: center;
    }
    .btn {
      display: inline-block;
      background: #004080;
      color: white;
      padding: 12px 25px;
      border-radius: 8px;
      text-decoration: none;
      margin-top: 20px;
    }
    .btn:hover {
      background: #00264d;
    }
    footer {
      background: #004080;
      color: white;
      text-align: center;
      padding: 30px 15px;
      margin-top: 40px;
    }
    footer img {
      height: 50px;
      display: block;
      margin: 0 auto 10px;
    }
    .social {
      margin-top: 20px;
      text-align: center;
    }
    .social a {
      margin: 0 10px;
      font-weight: bold;
      text-decoration: none;
      color: #004080;
    }
    .social a:hover {
      color: #0066cc;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <img src="images/logo.png" alt="Logo Gérard Business Services">
    <nav>
      <a href="#accueil">Accueil</a>
      <a href="#services">Services</a>
      <a href="#apropos">À propos</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero -->
  <section class="hero" id="accueil">
    <h1>La gestion immobilière en toute confiance</h1>
  </section>

  <!-- Services -->
  <section id="services">
    <h2>Nos Services</h2>
    <div class="services">
      <div class="service">
        <img src="images/gestion-locative.jpg" alt="Gestion locative">
        <p><strong>Gestion locative :</strong> Confiez-nous vos biens pour une gestion complète, du suivi des loyers à l’entretien.</p>
      </div>
      <div class="service">
        <img src="images/parcelles.jpg" alt="Vente et achat de parcelles">
        <p><strong>Vente & Achat de parcelles :</strong> Transactions sécurisées et accompagnement de bout en bout.</p>
      </div>
      <div class="service">
        <img src="images/entretien.jpg" alt="Entretien et nettoyage">
        <p><strong>Entretien :</strong> Gardez vos espaces toujours propres et agréables.</p>
      </div>
      <div class="service">
        <img src="images/gsm.jpg" alt="Maintenance GSM">
        <p><strong>Maintenance en GSM :</strong> Assistance et réparation rapide pour vos téléphones.</p>
      </div>
    </div>
  </section>

  <!-- A propos -->
  <section id="apropos">
    <h2>À propos</h2>
    <p style="text-align:center; max-width:800px; margin:auto;">
      Gérard Business Services est une entreprise spécialisée dans l’immobilier et les services professionnels. 
      Nous plaçons la confiance, la transparence et la satisfaction de nos clients au cœur de notre engagement. 
      Notre objectif est de vous simplifier la vie en vous offrant des solutions fiables et efficaces.
    </p>
  </section>

  <!-- Contact -->
  <section id="contact" class="contact">
    <h2>Contactez-nous</h2>
    <p>📞 Téléphone 1 (WhatsApp) : <a href="https://wa.me/2290162045039" target="_blank"><strong>+229 01 62 04 50 39</strong></a></p>
    <p>📞 Téléphone 2 : <strong>+229 01 44 58 70 88</strong></p>
    <p>📧 Email : <a href="mailto:gerardbusinessservice@gmail.com"><strong>gerardbusinessservice@gmail.com</strong></a></p>
    <p>📍 Adresse : Abomey-Calavi, Bénin</p>

    <div class="social">
      <a href="https://www.facebook.com/gerardbusinessservice
