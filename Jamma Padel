<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tournoi de Padel 2025 - Inscriptions</title>
  <style>
    body {
      font-family: "Poppins", sans-serif;
      background: linear-gradient(135deg, #00b4db, #0083b0);
      color: white;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    header {
      padding: 50px 20px;
    }
    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    p {
      font-size: 1.2em;
    }
    form {
      background: rgba(255, 255, 255, 0.1);
      padding: 30px;
      border-radius: 15px;
      width: 90%;
      max-width: 400px;
      margin: 20px auto;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
    }
    input, select, button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: none;
      border-radius: 5px;
      font-size: 1em;
    }
    input, select {
      background: rgba(255,255,255,0.9);
      color: #333;
    }
    button {
      background: #ffcc00;
      color: #333;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover {
      background: #ffe066;
    }
    #places {
      font-size: 1.3em;
      font-weight: bold;
      margin-top: 20px;
    }
    footer {
      margin-top: 40px;
      padding: 20px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>🏆 Tournoi de Padel 2025</h1>
    <p>Inscris-toi vite ! Seulement <span id="places">32</span> places disponibles.</p>
  </header>

  <form id="padelForm" action="https://formspree.io/f/TON_FORM_ID" method="POST">
    <input type="text" name="prenom" placeholder="Prénom" required />
    <input type="text" name="nom" placeholder="Nom" required />
    <input type="email" name="email" placeholder="Email" required />
    <input type="tel" name="telephone" placeholder="Téléphone" required />
    <select name="niveau" required>
      <option value="">Niveau de jeu</option>
      <option>Débutant</option>
      <option>Intermédiaire</option>
      <option>Avancé</option>
    </select>
    <button type="submit">S'inscrire</button>
  </form>

  <footer>
    © 2025 Tournoi de Padel – Organisé par ton équipe 💪
  </footer>

  <script>
    // Simulation compteur dynamique (exemple)
    let placesRestantes = 32;
    document.getElementById("padelForm").addEventListener("submit", function(e) {
      if (placesRestantes > 0) {
        placesRestantes--;
        document.getElementById("places").textContent = placesRestantes;
        alert("Merci pour ton inscription !");
      } else {
        e.preventDefault();
        alert("Désolé, les inscriptions sont complètes !");
      }
    });
  </script>
</body>
</html>
