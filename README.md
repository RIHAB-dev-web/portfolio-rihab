# Portfolio de Rihab / Rihab's Portfolio

Bienvenue sur mon portfolio en ligne !  
Welcome to my online portfolio!

Je suis *Rihab*, développeuse front-end & programmeuse C/C++ dédiée à transformer vos idées en réalité.  
I am *Rihab*, a front-end developer & C/C++ programmer dedicated to turning your ideas into reality.

Ce site présente mes projets en développement web (HTML/CSS) ainsi que mes petits outils logiciels réalisés en C/C++.  
This site showcases my web development projects (HTML/CSS) as well as small software tools I have created using C/C++.

N’hésitez pas à me contacter pour toute demande de mission freelance ou collaboration.  
Feel free to contact me for any freelance work or collaboration opportunities.

---

## Comment utiliser ce dépôt / How to use this repository

- Le fichier principal est Portfolio_Rihab.html  
- The main file is Portfolio_Rihab.html  

- Vous pouvez ouvrir ce fichier dans un navigateur pour voir mon portfolio  
- You can open this file in a browser to view my portfolio  

- Ce portfolio est responsive, adapté aux mobiles et ordinateurs  
- This portfolio is responsive and works well on both mobile devices and desktop computers  

---

<!DOCTYPE html>
<html lang="fr">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Design Durable</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <h1>Site Web Moderne & Éco-Responsable</h1>
      <p>Conçu avec HTML & CSS | Responsive | Accessible</p>
      <a href="#contact" class="btn">Me contacter</a>
    </header>

    <section class="features">
      <div class="card">
        <h2>🌱 Design Durable</h2>
        <p>Optimisé pour réduire l'empreinte numérique.</p>
      </div>
      <div class="card">
        <h2>📱 Responsive</h2>
        <p>Adapté à tous les écrans : mobile, tablette, desktop.</p>
      </div>
      <div class="card">
        <h2>💡 Code Propre</h2>
        <p>Structure claire, commentaires utiles, bonnes pratiques.</p>
      </div>
    </section>

    <footer id="contact">
      <p>Contactez-moi pour créer votre site web engagé.</p>
    </footer>
  </body>
</html>
/* Base */
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background-color: #f4f4f4;
  color: #333;
}

/* Header */
header {
  background-color: #e0ffe0;
  text-align: center;
  padding: 3rem 1rem;
}

header h1 {
  margin-bottom: 0.5rem;
  font-size: 2rem;
}

header p {
  margin-bottom: 1rem;
}

.btn {
  background-color: #4caf50;
  color: white;
  padding: 0.7rem 1.2rem;
  text-decoration: none;
  border-radius: 5px;
}

/* Features */
.features {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  padding: 2rem;
  gap: 1rem;
}

.card {
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  padding: 1.5rem;
  max-width: 300px;
  text-align: center;
}

/* Footer */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 1rem;
}

/* Responsive */
@media (max-width: 600px) {
  .features {
    flex-direction: column;
    align-items: center;
  }

  header h1 {
    font-size: 1.5rem;
  }
}

## Contact

- Email : [rihabdardani290@gmail.com](mailto:rihabdardani290@gmail.com)  
- Email: [rihabdardani290@gmail.com](mailto:rihabdardani290@gmail.com)  

- Profils freelance :  
  - Fiverr : (à venir)  
  - Upwork : (à venir)  

- Freelance profiles:  
  - Fiverr: (coming soon)  
  - Upwork: (coming soon)
