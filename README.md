# Treattower-S.A.S
<!TREATTOWER html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Treattower</title>
  <style>
    body {
      font-family: Times New Roman, sans-serif;
      font-size: 19px;
      background-color: #FFFFFF;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #DAB8E0;
      color: white;
      text-align: center;
      padding: 40px 20px;
    }
.encabezado {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 20px; /* espacio entre logo y texto */
}

.logo {
  width: 100px;   /* ajusta tamaño del logo */
  height: auto;
  border-radius: 10px; /* opcional, esquinas redondeadas */
}

    nav {
      background-color: #0090E8;
      padding: 15px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
      font-weight: bold;
      padding: 8px 12px;
      border-radius: 5px;
      transition: background 0.3s;
      cursor: pointer;
    }

    nav a:hover {
      background-color: #80DFFF;
    }

    section {
      display: none;
      padding: 30px;
      max-width: 900px;
      margin: auto;
    }

    section.active {
      display: block;
    }

    h2 {
      color: #2e8b57;
    }

    .resaltado {
      background-color: #FFFFFF;
      border-left: 4px solid #4caf50;
      padding: 10px;
      margin-bottom: 20px;
    }

    .cta-button {
      background-color: #2EB2FF;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      display: block;
      width: fit-content;
      margin: 20px auto 0 auto;
      cursor: pointer;
    }

    .cta-button:hover {
      background-color: #2EA8FF;
    }

    footer {
      background-color: #4caf50;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }

    ul {
      list-style: disc;
      padding-left: 20px;
    }
  </style>
</head>

<body>
  <header>
  <div class="encabezado">
    <img src="imagenes/logo.jpg" alt="Logo Treattower" width="150">
    <div class="titulo">
      <h1>Bienvenidos a TREATTOWER</h1>
      <p>Transformamos la distancia en cariño</p>
    </div>
  </div>
</header>



  <nav>
    <a onclick="mostrarSeccion('inicio')">Inicio</a>
    <a onclick="mostrarSeccion('quienes-somos')">¿Quiénes somos?</a>
    <a onclick="mostrarSeccion('que-es')">¿Qué es Treattower?</a>
    <a onclick="mostrarSeccion('como-funciona')">¿Cómo funciona?</a>
    <a onclick="mostrarSeccion('prototipo')">Prototipo</a>
    <a onclick="mostrarSeccion('beneficios')">Beneficios</a>
    <a onclick="mostrarSeccion('contacto')">Contáctanos</a>
  </nav>

  <!-- SECCIONES -->

  <section id="inicio" class="active">
  <h2>Inicio</h2>
  <div class="resaltado">
    <p><strong>Treattower</strong> es un innovador dispositivo inteligente diseñado para brindar un cuidado integral a las mascotas a través de la tecnología. Integra en una sola estructura un dispensador de alimento, agua y premios, junto con una cámara HD y un micrófono bidireccional que permiten la comunicación en tiempo real entre el dueño y su mascota. Además, incluye juguetes interactivos controlables desde una aplicación móvil, lo que garantiza entretenimiento, seguridad y bienestar aun cuando el propietario no se encuentre en casa. Su propósito principal es fortalecer el vínculo entre las personas y sus animales de compañía, ofreciendo comodidad, confianza y una experiencia moderna de cuidado.</p>
  </div>
    <p>
   Mi idea de TreatTower nació al pensar en cómo ayudar a las mascotas cuando sus dueños no están en casa, combinando tecnología y cariño para darles alimento, agua, premios y compañía en todo momento.
  </p>

  <!-- Misión -->
  <h3 style="color:#2e8b57;">Misión</h3>
  <div class="resaltado">
    <p>En TreatTower S.A.S. desarrollamos soluciones inteligentes que facilitan el cuidado de las mascotas aun en ausencia de sus dueños, garantizando alimentación, hidratación y entretenimiento de forma segura, eficiente y confiable.</p>
  </div>

  <!-- Visión -->
  <h3 style="color:#2e8b57;">Visión</h3>
  <div class="resaltado">
    <p>Para el año 2030, en TreatTower S.A.S. aspiramos a ser líderes en innovación para el cuidado de las mascotas, ofreciendo sistemas inteligentes que garanticen su bienestar y fortalezcan el vínculo con sus dueños desde cualquier lugar..</p>
  </div>

  <p><em>“Transformamos la distancia en cariño”</em></p>

  <a class="cta-button" onclick="mostrarSeccion('quienes-somos')">Conoce más</a>
</section>

  <section id="quienes-somos">
  <h2>¿Quiénes somos?</h2>
  <div class="resaltado">
    <p>Somos Sandy Segura,Paula Zarate , estudiantes del colegio Tomas Carrasquilla y estamos comprometidos con el bienestar de las mascotas y con el cuidado del planeta a través de un uso responsable de los recursos.
     <strong>Treattower</strong> es un proyecto innovador que integra tecnología para mejorar la relación entre las personas y sus mascotas. Ofrece alimentación, agua, premios y entretenimiento de forma remota, reduciendo el desperdicio de recursos, aumentando la eficiencia y aportando a la sostenibilidad ambiental 
TreatTower no solo responde a un problema tecnológico para el cuidado de mascotas, sino también a una necesidad social: apoyar a los dueños que, por trabajo o distancia, no pueden estar presentes todo el tiempo, darles más independencia en la gestión del bienestar de sus animales y contribuir al fortalecimiento del vínculo humano–mascota .</p>
  </div>
  <p>
Mi proyecto nace del deseo de TreatTower es tecnología accesible para el cuidado de tus mascotas: alimento, agua, juegos y compañía, todo al alcance de un clic. Porque la innovación también debe estar al servicio de quienes más queremos. 
</p>

  <!-- FOTO EQUIPO -->
  <div style="text-align:center; margin-top:20px;">
   <img src="imagenes/equipo.jpg" alt="Integrantes de Treattower" 
     width="400" style="border-radius:10px; box-shadow:0px 4px 10px rgba(0,0,0,0.2);">
    <p><em>Integrantes de Treatower</em></p>
  </div>
</section>


  <section id="que-es">
  <h2>¿Qué es Treattower?</h2>
  <div class="resaltado">
    <p>
      <strong>Treattower</strong> es un dispositivo tecnológico innovador que busca transformar la manera en la que los dueños cuidan a sus mascotas. Está diseñado para brindar una experiencia completa que integra alimentación, hidratación, entretenimiento y comunicación en un solo equipo.

    </p>
  </div>

  <p>
     <strong>Treattower</strong> 
    <em>Dispensador Inteligente</em>

Una de sus principales funciones es el dispensador de comida, agua y premios, que garantiza que la mascota reciba la cantidad adecuada de alimento incluso cuando su dueño no se encuentra en casa. Además, incluye una cámara HD y un micrófono bidireccional que permiten la interacción en tiempo real, haciendo posible ver, escuchar y hablar con la mascota desde cualquier lugar.
El entretenimiento también es fundamental, por eso TreatTower incorpora juguetes interactivos que pueden controlarse desde una aplicación móvil. De esta manera, no solo se asegura el bienestar físico y mental de la mascota, sino que también se refuerza el vínculo emocional con su dueño.  
   El objetivo de este proyecto es ofrecer a los cuidadores la tranquilidad de que sus mascotas están seguras, activas y acompañadas, incluso a la distancia. Con Treattower, la tecnología se convierte en un puente de amor y cuidado, garantizando una vida más feliz y saludable para los animales de compañía. 
  </p>
</section>


  <section id="como-funciona">
  <h2>¿Cómo funciona?</h2>
  <p>
  <strong>Treattower</strong> funciona a través de la integración de un dispositivo físico y una aplicación móvil conectados mediante internet. Su sistema está diseñado para que los dueños tengan el control total del cuidado de sus mascotas en tiempo real, sin importar la distancia.
  </p>

  <ul>
  <li>
    <strong>Conexión inteligente:</strong>  
    El dispositivo se conecta a la red WiFi del hogar y se sincroniza con la aplicación móvil. 
    Desde allí, el dueño puede gestionar todas las funciones de TreatTower de manera sencilla e intuitiva.
  </li>

  <li>
    <strong>Alimentación y agua automática:</strong>  
    El dispensador de comida libera porciones programadas o manuales según la necesidad de la mascota. 
    El sistema de agua mantiene el recipiente siempre lleno y limpio, garantizando hidratación continua.
  </li>

  <li>
    <strong>Premios y recompensas:</strong>  
    El dueño puede activar el dispensador de snacks desde la app para premiar a la mascota en momentos específicos, reforzando su buen comportamiento aun estando lejos.
  </li>

  <li>
    <strong>Cámara y micrófono bidireccional:</strong>  
    La cámara HD transmite en vivo lo que hace la mascota. Con el micrófono y altavoz integrados, es posible hablarle o escucharla, generando cercanía y tranquilidad.
  </li>

  <li>
    <strong>Juguetes interactivos:</strong> 
    El dispositivo incluye juegos controlables desde el celular que mantienen a la mascota activa, entretenida y estimulada mentalmente.
  </li>

  <li>
    <strong>Seguridad y bienestar:</strong>  
    Los sensores del equipo permiten detectar movimientos o comportamientos inusuales. Esto da un plus de seguridad, asegurando que la mascota esté siempre protegida.
  </li>
</ul>

  <p>
 TreatTower funciona como un cuidador digital completo, que combina tecnología, comodidad y amor para garantizar el bienestar de las mascotas y la tranquilidad de sus dueños.
  </p>
</section>


  <section id="prototipo">
  <h2>Prototipo</h2>
  <p>
    El prototipo de <strong>Treattower</strong> está diseñado como una maqueta no funcional que representa el cuidado integral de las mascotas.
  </p>

  <p>
   En ella se integran de forma visual el dispensador de alimento, el sistema de agua, la cámara, el micrófono, los premios y los juguetes interactivos, mostrando cómo cada elemento se conecta para brindar bienestar.
Aunque aún no cumple todas sus funciones reales, este prototipo sirve como una demostración clara de la idea y permite explicar cómo, a través de la aplicación móvil, el dueño puede tener el control en tiempo real de la alimentación, hidratación, entretenimiento y comunicación con su mascota.
  </p>

  <!-- FOTO DEL PROTOTIPO -->
  <div style="text-align:center; margin-top:20px;">
    <img src="imagenes/prototipo.jpg" alt="Prototipo Treattower" width="500" 
         style="border-radius:10px; box-shadow:0px 4px 10px rgba(0,0,0,0.3);">
    <p><em>Prototipo del Dispensador Inteligente</em></p>
  </div>
</section>


 <section id="beneficios">
  <h2>Beneficios</h2>
  <div class="resaltado">
    <p>
      Con <strong>Treattower</strong> no solo logramos un cuidado más eficiente de las mascotas,
también apoyamos a los dueños a fortalecer el vínculo con ellas de manera práctica y responsable.
Estos son algunos de los principales beneficios de TreatTower:
    </p>
  </div>

  <ul>
    <li><strong>Alimentación y agua aseguradas:</strong> Garantiza que tu mascota tenga comida y agua fresca incluso cuando no estás en casa.</li>
    <li><strong>Comunicación en tiempo real:</strong> Con cámara y micrófono puedes verla, escucharla y hablarle en cualquier momento.</li>
    <li><strong>Entretenimiento interactivo:</strong> Los juguetes controlados desde la app mantienen a tu mascota activa y feliz.</li>
    <li><strong>Premios a distancia:</strong> Refuerza su buen comportamiento con snacks desde donde estés..</li>
    <li><strong>Tranquilidad total:</strong> Sabes que tu mascota está cuidada, acompañada y segura siempre.</li>
    <li><strong>La aplicación móvil:</strong> La app permite al dueño tener el control total del dispositivo desde cualquier lugar..</li>
  </ul>

  <p>
    En conclusión, <strong>Treattower</strong> Treattower demuestra que la tecnología puede ser un puente entre las mascotas y sus dueños, ofreciendo alimentación, agua, entretenimiento y comunicación en un solo dispositivo. Este proyecto garantiza bienestar y seguridad para los animales, al mismo tiempo que brinda tranquilidad y cercanía a quienes los cuidan, incluso a la distancia. Más que un prototipo, Treattower es una propuesta innovadora con gran potencial para transformar la manera en que compartimos el día a día con nuestras mascotas..
  </p>
</section>

  <section id="contacto">
  <h2>Contáctanos</h2>
  <div class="resaltado">
    <p>
      ¿Quieres saber más sobre <strong>Treattower</strong> o apoyarnos en este proyecto?  
      Escríbenos o síguenos en nuestras redes sociales. ¡Estaremos felices de compartir más sobre nuestro trabajo contigo!
    </p>
  </div>

  <p>★ <strong>Correo:</strong> <a href="mailto:treattower24@gmail.com">treattower24@gmail.com</a></p>
  <p>★ <strong>Instagram:</strong> <a href="https://www.instagram.com/treatower?igsh=MXZjeTEzMTJndzdzdQ==" target="_blank">@treattower</a></p>
  <p>★ <strong>TikTok:</strong> <a href="https://vm.tiktok.com/ZSHnSgceDg9V4-38JHz/" target="_blank">@treattower</a></p>
  <p>★ <strong>Facebook:</strong> <a href="https://www.facebook.com/share/19eAngfV3a/" target="_blank">Treattower Ter</a></p>
  <p>★ <strong>Localización:</strong> Cl. 74 #62-44, Bogotá</p>

  <!-- BOTONES DE ACCESO RÁPIDO -->
  <div style="text-align:center; margin-top:20px;">
    <a href="mailto:treattower24@gmail.com" class="cta-button">📩 Enviar correo</a>
    <a href="https://www.instagram.com/treatower?igsh=MXZjeTEzMTJndzdzdQ==" target="_blank" class="cta-button">📷 Instagram</a>
    <a href="https://vm.tiktok.com/ZSHnSgceDg9V4-38JHz/" class="cta-button">🎵 TikTok</a>
    <a href="https://www.facebook.com/share/19eAngfV3a/"_blank" class="cta-button">📘 Facebook</a>
  </div>
</section>


  <footer>
    <p>© 2025 Treattower | Proyecto académico ExpoTomás</p>
  </footer>

  <script>
    function mostrarSeccion(id) {
      const secciones = document.querySelectorAll('section');
      secciones.forEach(seccion => {
        seccion.classList.remove('active');
      });

      const activa = document.getElementById(id);
      if (activa) {
        activa.classList.add('active');
        window.scrollTo(0, 0);
      }
    }
  </script>
</body>
</html>
