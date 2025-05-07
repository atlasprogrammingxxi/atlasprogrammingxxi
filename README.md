<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Hello There! | Hermel Rojas</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      margin: 0;
      padding: 0;
      color: #222;
    }
    main {
      max-width: 700px;
      margin: 40px auto;
      background: #fff;
      padding: 36px 24px 24px 24px;
      border-radius: 10px;
      box-shadow: 0 4px 24px rgba(0,0,0,0.09);
    }
    h1 {
      font-size: 2.2em;
      margin-bottom: 18px;
      color: #0072c6;
    }
    .contact-section {
      margin: 36px 0 28px 0;
      text-align: center;
    }
    .contact-title {
      font-size: 1.5em;
      margin-bottom: 18px;
      font-weight: bold;
      color: #333;
    }
    .contact-buttons {
      display: flex;
      justify-content: center;
      gap: 16px;
      margin-bottom: 10px;
    }
    .contact-button {
      padding: 12px 28px;
      border-radius: 6px;
      font-size: 1em;
      font-weight: bold;
      text-decoration: none;
      color: #fff;
      transition: background 0.2s;
      box-shadow: 0 2px 8px rgba(0,0,0,0.07);
      display: inline-block;
    }
    .whatsapp-btn {
      background: #25D366;
    }
    .whatsapp-btn:hover {
      background: #1ebe5d;
    }
    .email-btn {
      background: #0072c6;
    }
    .email-btn:hover {
      background: #005fa3;
    }
    h4 {
      margin-top: 36px;
      color: #444;
    }
    ul {
      margin: 0 0 24px 20px;
      padding: 0;
    }
    li {
      margin-bottom: 8px;
      font-size: 1.05em;
    }
    blockquote {
      margin: 30px 0 0 0;
      padding: 16px 24px;
      background: #f1f7fb;
      border-left: 4px solid #0072c6;
      color: #333;
      font-style: italic;
    }
    @media (max-width: 600px) {
      main {
        padding: 16px 4vw;
      }
      .contact-buttons {
        flex-direction: column;
        gap: 12px;
      }
    }
  </style>
</head>
<body>
<main>
  <h1>About me</h1>
  <p>
    Hello! I'm Hermel Francisco Rojas, a bilingual (Spanish/English C1) Full Stack Developer and Systems Engineering student based in Bogotá, Colombia. I have experience designing, developing, and deploying scalable web applications, with strong command of both frontend (CSS, Vue, React) and backend (Java, Spring Boot, JavaScript, NodeJS) technologies.
    <br><br>
    My background includes building intuitive and responsive user interfaces, implementing robust backend logic, and managing databases and APIs for efficient data handling. I have successfully led and collaborated on projects from conception to deployment, always focusing on delivering innovative solutions and enhancing user experience. Here is some info about me:
  </p>

  <section class="contact-section">
    <div class="contact-title">How to contact me</div>
    <div class="contact-buttons">
      <a href="https://wa.me/1234567890" target="_blank" class="contact-button whatsapp-btn">
        WhatsApp
      </a>
      <a href="mailto:francisco_rojasxxi@hotmail.es" class="contact-button email-btn">
        Email
      </a>
    </div>
  </section>

  <h4>📫 How to reach me</h4>
  <ul>
    <li>🙃 Pronouns: He/Him/They/Them</li>
    <li>👀 I’m interested in <a href="https://www.oracle.com/in/java/" target="_blank">Java</a>. I know JavaScript, HTML and CSS.</li>
    <li>💞️ I’m looking to collaborate on anything, you can contact me for collaboration!</li>
  </ul>

  <blockquote>
    You can know if I am active on Github, by looking at my GitHub status. It updates when I become online or when I am sleeping.
  </blockquote>
</main>
</body>
</html>
