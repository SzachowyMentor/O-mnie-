<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>O mnie</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
      color: #333;
    }
    
    .about-container {
      max-width: 800px;
      margin: 50px auto;
      background-color: #fff;
      border: 2px solid #ccc;
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    
    h1 {
      text-align: center;
      margin-bottom: 20px;
    }
    
    .about-content {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
    }
    
    .profile-img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 2px solid #ccc;
      margin-right: 20px;
      object-fit: cover;
    }
    
    .bio {
      flex: 1;
      line-height: 1.6;
    }
    
    @media (max-width: 600px) {
      .about-content {
        flex-direction: column;
        text-align: center;
      }
      
      .profile-img {
        margin-right: 0;
        margin-bottom: 20px;
      }
    }
  </style>
</head>
<body>
  <div class="about-container">
    <h1>O mnie</h1>
    <div class="about-content">
      <!-- Dodaj swoje zdjęcie profilowe -->
      <img src="profilowe.jpg" alt="Moje zdjęcie profilowe" class="profile-img">
      <div class="bio">
        <p>Nazywam się Jan Kowalski. Jestem pasjonatem technologii i programowania, a moją specjalnością jest tworzenie nowoczesnych stron internetowych. Interesuję się również fotografią oraz podróżami, które inspirują mnie do ciągłego rozwoju.</p>
        <p>Posiadam umiejętności w zakresie HTML, CSS, JavaScript, a także programowania w Pythonie. W swojej pracy cenię sobie precyzję, kreatywność oraz nieustanne poszukiwanie nowych rozwiązań.</p>
      </div>
    </div>
  </div>
</body>
</html>
