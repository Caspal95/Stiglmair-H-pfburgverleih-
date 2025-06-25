# Stiglmair-H-pfburgverleih<!DOCTYPE html><html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hüpfburgverleih Stiglmair</title>
  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #ffa500; /* Orange */
      --accent: #00b7c2; /* Türkis */
      --light: #ffffff;
      --dark: #262626;
    }* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Nunito', sans-serif;
}

body {
  color: var(--dark);
  background: var(--light);
  line-height: 1.6;
}

header {
  background: var(--primary);
  color: var(--light);
  padding: 1rem 2rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}

header h1 {
  font-size: 1.6rem;
  letter-spacing: 1px;
}

nav a {
  color: var(--light);
  text-decoration: none;
  margin-left: 1rem;
  font-weight: 600;
  transition: opacity 0.2s ease-in-out;
}

nav a:hover {
  opacity: 0.8;
}

.hero {
  height: 50vh;
  background: url('https://placehold.co/1600x800?text=Hero+Bild') center/cover no-repeat;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 2rem;
}

.hero h2 {
  font-size: 2.2rem;
  background: rgba(255,255,255,0.85);
  padding: 1rem 2rem;
  border-radius: 12px;
}

.container {
  width: 90%;
  max-width: 1100px;
  margin: 2rem auto;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.5rem;
}

.card {
  border: 2px solid var(--accent);
  border-radius: 20px;
  overflow: hidden;
  background: var(--light);
  box-shadow: 0 8px 16px rgba(0,0,0,0.05);
  transition: transform 0.2s;
}

.card:hover { transform: translateY(-4px); }

.card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

.card-body {
  padding: 1rem;
}

.card-body h3 { margin-bottom: 0.5rem; }

.price {
  margin: 0.5rem 0 1rem;
  font-weight: 700;
  color: var(--primary);
}

.btn {
  display: inline-block;
  background: var(--accent);
  color: var(--light);
  padding: 0.6rem 1.2rem;
  border: none;
  border-radius: 30px;
  cursor: pointer;
  text-decoration: none;
  font-weight: 600;
  transition: opacity 0.2s ease-in-out;
}

.btn:hover { opacity: 0.85; }

/* Form Section */
.form-section {
  background: var(--accent);
  color: var(--light);
  padding: 2rem 0;
}

.form-section h2 {
  text-align: center;
  margin-bottom: 1rem;
}

form {
  width: 90%;
  max-width: 600px;
  margin: 0 auto;
  display: grid;
  gap: 1rem;
}

label { font-weight: 600; }

input, select {
  padding: 0.6rem;
  border-radius: 8px;
  border: none;
  font-size: 1rem;
}

input[type="checkbox"] {
  width: 1.2rem;
  height: 1.2rem;
}

.checkbox-wrap {
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

footer {
  text-align: center;
  padding: 1rem;
  background: #f5f5f5;
  font-size: 0.9rem;
}

@media (max-width: 600px) {
  .hero h2 { font-size: 1.5rem; }
}

  </style>
</head>
<body>
  <header>
    <h1>Hüpfburgverleih Stiglmair</h1>
    <nav>
      <a href="#burgen">Hüpfburgen</a>
      <a href="#anfrage">Reservierung</a>
      <a href="#kontakt">Kontakt</a>
    </nav>
  </header>  <section class="hero">
    <h2>Mach dein Event unvergesslich – miete jetzt eine Hüpfburg!</h2>
  </section>  <main class="container" id="burgen">
    <h2 style="text-align:center;margin-bottom:1rem;">Unsere Hüpfburgen</h2>
    <div class="cards">
      <!-- Super-Blocks -->
      <div class="card">
        <img src="https://placehold.co/400x300?text=Super+Blocks" alt="Super Blocks Hüpfburg" />
        <div class="card-body">
          <h3>Super-Blocks</h3>
          <p class="price">80€ Mo–Do • 90€ Fr–So</p>
          <a href="#anfrage" class="btn">Verfügbarkeit prüfen</a>
        </div>
      </div>
      <!-- Feuerwehr -->
      <div class="card">
        <img src="https://placehold.co/400x300?text=Feuerwehr" alt="Feuerwehr Hüpfburg" />
        <div class="card-body">
          <h3>Feuerwehr</h3>
          <p class="price">70€ Mo–Do • 80€ Fr–So</p>
          <a href="#anfrage" class="btn">Verfügbarkeit prüfen</a>
        </div>
      </div>
      <!-- Piratenschiff -->
      <div class="card">
        <img src="[https://placehold.co/400x300?text=Piratenschiff](https://kiddyfun.de/media/f5/4f/d7/1614424990/Springburg%20aufblasbar%20Piratenschiff%20kaufen%20-%20F2.jpg)" alt="Piratenschiff Hüpfburg" />
        <div class="card-body">
          <h3>Piratenschiff</h3>
          <p class="price">70€ Mo–Do • 80€ Fr–So</p>
          <a href="#anfrage" class="btn">Verfügbarkeit prüfen</a>
        </div>
      </div>
      <!-- Koala -->
      <div class="card">
        <img src="https://placehold.co/400x300?text=Koala" alt="Koala Hüpfburg" />
        <div class="card-body">
          <h3>Koala</h3>
          <p class="price">70€ Mo–Do • 80€ Fr–So</p>
          <a href="#anfrage" class="btn">Verfügbarkeit prüfen</a>
        </div>
      </div>
    </div>
  </main>  <!-- Formular -->  <section class="form-section" id="anfrage">
    <h2>Reservierungsanfrage</h2>
    <form id="booking-form">
      <label for="burg">Hüpfburg wählen *</label>
      <select id="burg" name="Burg" required>
        <option value="Super-Blocks">Super-Blocks</option>
        <option value="Feuerwehr">Feuerwehr</option>
        <option value="Piratenschiff">Piratenschiff</option>
        <option value="Koala">Koala</option>
      </select><label for="date">Wunschtermin *</label>
  <input type="date" id="date" name="Datum" required />

  <label for="name">Ihr Name *</label>
  <input type="text" id="name" name="Name" placeholder="Max Mustermann" required />

  <label for="email">E-Mail *</label>
  <input type="email" id="email" name="E-Mail" placeholder="max@example.de" required />

  <label for="phone">Telefon</label>
  <input type="tel" id="phone" name="Telefon" placeholder="0151 234567" />

  <div class="checkbox-wrap">
    <input type="checkbox" id="lieferung" name="Lieferung" value="Ja" />
    <label for="lieferung">Lieferung bis 15km (+25€)</label>
  </div>

  <button type="submit" class="btn">Anfrage senden</button>
</form>

  </section>  <footer id="kontakt">
    &copy; 2025 Hüpfburgverleih Stiglmair • E-Mail: <a href="mailto:Stiglmair.Huepfburgverleih@gmx.net">Stiglmair.Huepfburgverleih@gmx.net</a>
  </footer>  <script>
    /* === Formspree / EmailJS Integration ===
       Variante 1: Formspree
       1. Registriere dich kostenlos auf https://formspree.io
       2. Erstelle ein neues Formular und kopiere die Endpoint-URL (z.B. https://formspree.io/f/xyzabc)
       3. Ersetze die URL unten in fetch() oder nutze <form action="URL" method="POST"> ohne JS.

       Variante 2: EmailJS (https://www.emailjs.com/) – ebenfalls kostenlos bis 200 E-Mails / Monat
    */

    const form = document.getElementById('booking-form');

    form.addEventListener('submit', async (e) => {
      e.preventDefault();

      // Formulardaten sammeln
      const formData = new FormData(form);

      try {
        // === HIER Formspree-URL einfügen ===
        const endpoint = 'https://formspree.io/f/yourFormID'; // TODO: ersetzen!

        const response = await fetch(endpoint, {
          method: 'POST',
          headers: {
            'Accept': 'application/json'
          },
          body: formData
        });

        if (response.ok) {
          alert('Vielen Dank! Deine Anfrage wurde versendet.');
          form.reset();
        } else {
          alert('Ups! Etwas ist schiefgelaufen. Bitte versuche es später erneut.');
        }
  
      } catch (err) {
        alert('Verbindungsfehler – bitte später erneut versuchen.');
        console.error(err);
      }
    });
  </script></body>
</html>
