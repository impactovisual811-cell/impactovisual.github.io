<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Impacto Visual - Publicidad y Anuncios</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap');

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #000;
      color: #d4af37;
      text-align: center;
      scroll-behavior: smooth;
    }

    header {
      padding: 40px 20px;
      animation: fadeInDown 1s ease forwards;
    }

    /* Logo dorado en base64 */
    .logo {
      width: 120px;
      height: 120px;
      margin: 0 auto 20px auto;
      animation: rotate 20s linear infinite;
    }

    h1 {
      color: #d4af37;
      font-size: 2.8em;
      margin: 10px 0;
      font-weight: 600;
      text-shadow: 0 0 6px #d4af37;
    }

    p.emphasis {
      font-style: italic;
      font-weight: 300;
      color: #b8860b;
      text-shadow: 0 0 4px #b8860b;
    }

    section {
      padding: 50px 20px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: #b8860b;
      margin-bottom: 40px;
      font-weight: 600;
      font-size: 2.2em;
      text-shadow: 0 0 6px #b8860b;
    }

    .servicio {
      background: rgba(212,175,55,0.1);
      border: 1px solid #d4af37;
      border-radius: 12px;
      margin: 20px auto;
      padding: 25px;
      max-width: 600px;
      box-shadow: 0 0 12px rgba(212,175,55,0.6);
      transition: transform 0.3s ease;
    }

    .servicio:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px rgba(212,175,55,0.9);
    }

    form {
      max-width: 450px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    input, textarea {
      padding: 12px;
      border: 1.5px solid #d4af37;
      background: black;
      color: #d4af37;
      border-radius: 8px;
      font-size: 1em;
      font-weight: 300;
      box-shadow: 0 0 8px rgba(212,175,55,0.4);
      transition: border-color 0.3s ease;
    }

    input:focus, textarea:focus {
      outline: none;
      border-color: #b8860b;
      box-shadow: 0 0 12px #b8860b;
      background: #111;
    }

    button {
      background: #d4af37;
      color: black;
      border: none;
      padding: 15px;
      font-weight: 600;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1.1em;
      box-shadow: 0 0 12px #d4af37;
      transition: background 0.3s ease;
    }

    button:hover {
      background: #b8860b;
    }

    footer {
      background: #111;
      padding: 20px;
      color: #888;
      font-size: 0.9em;
      text-align: center;
    }

    a.whatsapp {
      display: inline-block;
      background: #25D366;
      color: white;
      padding: 14px 25px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 700;
      font-size: 1.1em;
      box-shadow: 0 0 14px #25D366;
      margin-top: 25px;
      transition: background 0.3s ease;
    }

    a.whatsapp:hover {
      background: #1ebe57;
    }

    /* Animaciones */
    @keyframes rotate {
      from { transform: rotate(0deg);}
      to { transform: rotate(360deg);}
    }

    @keyframes fadeInDown {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Responsive */
    @media (max-width: 600px) {
      h1 {
        font-size: 2em;
      }
      h2 {
        font-size: 1.8em;
      }
      .servicio {
        max-width: 100%;
      }
      form {
        max-width: 100%;
      }
    }
  </style>
</head>
<body>

  <header>
    <img class="logo" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAJAAAACQCAMAAABaP+fcAAABl1BMVEVHcEz///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////8h0prVAAAAV3RSTlMAAgQJBhsNEhgYGh0nJCcoKisuLzAxNjM1Ojw+QkZGT1FSX2FpbWhxeXt/gYSEjo+QkpSVmJucn6Smp6iqrLCytLi7uLq+vr7BwsTFy87Mz9DU09TV1tfY2d7f4OHi5FTVQAAAIpJREFUeNrt0tlygzAYBdCkSbZLdu22u7v7/M3CsFIOmBIjuPs7P69h+xohoWATNYXq+KFGVJTkIzIKmF1HJIM+4IBz2q0uXIvOnWKIUkLOKaVYzGiIzS3AJLqArPupZBNOaBopXBB3qB8KIdURy84wG9KSuBJNVp6txIwTYmXDYECXHIOZHGtpbOmQwlPdSBNUn0RI7hP7wi0Uu3C3ytXkq0yk03eUM8XKGqx4Dn9mDyhvCuh14tAsfkLfh0ccQi93bBJOu5t2v3aZZefAeOUcAMZ4qYleSEdLVxAYXvAQrsFvQ8oZV4PKDsLKCs0A04PbhuDd6C6FkPkFowt6WqpO1DRH5cwcmr22+AjxEKxSCplRX6J9OsTME/QGEGxX93D+XAC3nrSEiIKufUsAAAAASUVORK5CYII=" alt="Logo Impacto Visual" />
    <h1>Impacto Visual</h1>
    <p class="emphasis">Publicidad que deja huella</p>
  </header>

  <section id="servicios">
    <h2>Servicios</h2>
    <div class="servicio">
      <h3>Diseño de Publicidad</h3>
      <p>Desde flyers hasta campañas digitales, creamos imágenes que impactan.</p>
    </div>
    <div class="servicio">
      <h3>Gestión de Anuncios</h3>
      <p>Nos encargamos de tus campañas en redes para maximizar tus resultados.</p>
    </div>
    <div class="servicio">
      <h3>Producción Audiovisual</h3>
      <p>Videos y animaciones para mostrar tu marca de forma profesional.</p>
    </div>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <form action="mailto:Impactovisual811@gmail.com" method="POST" enctype="text/plain">
      <input type="text" name="nombre" placeholder="Tu nombre" required />
      <input type="email" name="correo" placeholder="Tu correo" required />
      <textarea name="mensaje" rows="4" placeholder="Cuéntanos tu idea"></textarea>
      <button type="submit">Enviar</button>
    </form>

    <a class="whatsapp" href="https://wa.me/56932547471" target="_blank" rel="noopener noreferrer">📱 Enviar mensaje por WhatsApp</a>
  </section>

  <footer>
    <p>© 2025 Impacto Visual. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
