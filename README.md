<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Feuerwehr Neuenhof | Ausbildungsportal</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
  <style>
    /* Basis-Styles */
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #f9f9f9;
      color: #000;
      line-height: 1.5;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    .header {
      display: flex;
      align-items: center;
      background-color: #f4f4f4;
      padding: 20px;
      border-radius: 8px;
      border-bottom: 2px solid #ddd;
      margin-bottom: 30px;
    }

    .header img {
      height: 85px;
      width: auto;
      margin-right: 20px;
    }

    .header h1 {
      font-size: 32px;
      margin: 0;
      font-weight: 700;
    }

    .header p {
      margin-top: 5px;
      font-size: 16px;
      color: #555;
    }

    .section {
      max-width: 1000px;
      margin: 0 auto 40px;
      padding: 0 20px;
    }

    .section h2 {
      font-size: 28px;
      border-bottom: 2px solid #ddd;
      padding-bottom: 10px;
      margin-bottom: 20px;
    }

    .cards {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .card {
      background-color: #fff;
      border-radius: 8px;
      padding: 15px;
      text-align: center;
      flex: 1 1 250px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }

    .card:hover {
      transform: translateY(-3px);
      box-shadow: 0 5px 10px rgba(0,0,0,0.15);
    }

    .card img {
      width: 100%;
      max-width: 220px;
      margin-bottom: 10px;
    }

    .card p {
      margin: 0;
      font-size: 14px;
      color: #555;
    }

    @media (max-width: 600px) {
      .header {
        flex-direction: column;
        text-align: center;
      }

      .header img {
        margin-bottom: 10px;
      }
    }
  </style>
</head>
<body>

  <div class="header">
    <img src="https://github.com/user-attachments/assets/e955bb15-66d1-4238-b702-5f1ad34a22d2" alt="Logo Feuerwehr Neuenhof">
    <div>
      <h1>Feuerwehr Neuenhof | Ausbildungsportal</h1>
      <p>Das interaktive Nachschlagewerk für unsere Mannschaft</p>
    </div>
  </div>

  <div class="section">
    <h2>Willkommen im Ausbildungs-Repository</h2>
    <p>Deine digitale Anlaufstelle für das Schweizer Feuerwehr-Basiswissen (FKS) für unsere Feuerwehr Neuenhof.</p>
  </div>

  <div class="section">
    <h2>Abschnitt 6: Brandbekämpfung</h2>
    <p>Dieses Modul behandelt die feuerwehrtechnischen Grundlagen der Brandbekämpfung.</p>

    <div class="cards">
      <a href="https://docs.feukos.ch/Basiswissen/ReglementBasiswissenDE/?page=103" class="card">
        <img src="https://img.shields.io/badge/Offizielles-Basiswissen-0052cc?style=for-the-badge&logo=gitbook&logoColor=white" alt="Basiswissen">
        <p>FKS Reglement nachschlagen</p>
      </a>
      <a href="https://youtu.be/-iZpxEsfn0k" class="card">
        <img src="https://img.shields.io/badge/Video-Hydrantenbedienung-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Video Hydrant">
      </a>
      <a href="https://feuerwehr-neuenhof-ausbildung.shinyapps.io/Shiny_Brandbekaempfung/" class="card">
        <img src="https://img.shields.io/badge/Lern--App-Quiz_starten-28a745?style=for-the-badge&logo=rstudio&logoColor=white" alt="Shiny App">
        <p>Hier Wissen testen!</p>
      </a>
    </div>
  </div>

</body>
</html>
