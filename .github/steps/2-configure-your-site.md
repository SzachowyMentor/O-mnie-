<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kontakt</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 20px;
      color: #333;
    }
    
    .contact-wrapper {
      max-width: 600px;
      margin: 0 auto;
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    
    h1 {
      text-align: center;
      margin-bottom: 20px;
    }
    
    form .form-group {
      margin-bottom: 15px;
    }
    
    form label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }
    
    form input[type="text"],
    form input[type="email"],
    form textarea {
      width: 100%;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
    }
    
    form textarea {
      resize: vertical;
      min-height: 100px;
    }
    
    form button {
      display: block;
      width: 100%;
      background-color: #007BFF;
      color: #fff;
      border: none;
      padding: 12px;
      font-size: 1em;
      border-radius: 4px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    
    form button:hover {
      background-color: #0056b3;
    }
    
    .map-container {
      margin-top: 20px;
      position: relative;
      padding-top: 56.25%; /* 16:9 aspect ratio */
      overflow: hidden;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    
    .map-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      border: 0;
    }
  </style>
</head>
<body>
  <div class="contact-wrapper">
    <h1>Kontakt</h1>
    <form action="#" method="post">
      <div class="form-group">
        <label for="fullName">Imię i nazwisko</label>
        <input type="text" id="fullName" name="fullName" placeholder="Wpisz swoje imię i nazwisko" required>
      </div>
      <div class="form-group">
        <label for="email">Adres e-mail</label>
        <input type="email" id="email" name="email" placeholder="Wpisz swój adres e-mail" required>
      </div>
      <div class="form-group">
        <label for="message">Wiadomość</label>
        <textarea id="message" name="message" placeholder="Wpisz treść wiadomości" required></textarea>
      </div>
      <button type="submit">Wyślij</button>
    </form>
    <div class="map-container">
      <!-- Osadzona mapa Google Maps -->
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2436.633411582802!2d21.0090!3d52.2297!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x471ecd0be80a0011%3A0x86be9a111222!2sWarszawa%2C%20Polska!5e0!3m2!1spl!2sus!4v1600000000000" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
    </div>
  </div>
</body>
</html>
