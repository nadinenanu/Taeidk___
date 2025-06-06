<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Taeidk</title>
  <style>
    body {
      background-color: #ffeaf5;
      font-family: 'Arial', sans-serif;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      text-align: center;
      background-color: #ffcce5;
      padding: 20px;
    }
    header img {
      height: 100px;
    }
    header h1 {
      margin: 10px 0;
    }
    nav a {
      margin: 0 15px;
      color: #a03a6f;
      text-decoration: none;
      font-weight: bold;
    }
    .productos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .producto {
      background-color: #fff0f5;
      border: 2px solid #ffcce5;
      border-radius: 10px;
      padding: 15px;
      margin: 15px;
      width: 250px;
      text-align: center;
      box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
    }
    .producto img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .producto button {
      background-color: #ff99cc;
      color: white;
      border: none;
      padding: 10px 15px;
      margin-top: 10px;
      border-radius: 5px;
      cursor: pointer;
    }
    .producto button:hover {
      background-color: #ff66b2;
    }
    footer {
      background-color: #ffcce5;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <header>
    <img src="Taeidk.jpg" alt="Logo Taeidk">
    <h1>Taeidk</h1>
    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="inicio" class="productos">

    <!-- PRODUCTOS EXISTENTES A PARTIR DE AQUÍ -->
    <!-- (Ya están: Luffy, Barco los simpsons, Boyfriends, Gary) -->

    <!-- PRODUCTO: Charlie y Nick -->
    <div class="producto">
      <img src="Charlie y nick.jpg" alt="Charlie y Nick">
      <h3>Charlie y Nick "Heartstopper"</h3>
      <p>Cada cuadro está hecho a mano desde 0, el tiempo de realización depende de los detalles y tamaños. El tiempo mínimo son dos semanas, puede ser más como menos dependiendo del cuadro.</p>
      <label for="tamano-charlie">Tamaño:</label>
      <select id="tamano-charlie">
        <option value="20x15">$10.000 - 20x15</option>
        <option value="20x20">$12.500 - 20x20</option>
        <option value="28x23">$14.000 - 28x23</option>
        <option value="30x20">$16.500 - 30x20</option>
        <option value="30x30">$18.000 - 30x30</option>
        <option value="35x25">$20.500 - 35x25</option>
      </select>
      <br>
      <button onclick="comprar('Charlie y Nick Heartstopper', 'tamano-charlie')">Comprar por WhatsApp</button>
    </div>

    <!-- PRODUCTO: Finn y Jake -->
    <div class="producto">
      <img src="Finn y jake.jpg" alt="Finn y Jake">
      <h3>Finn y Jake "Hora de aventura"</h3>
      <p>Cada cuadro está hecho a mano desde 0, el tiempo de realización depende de los detalles y tamaños. El tiempo mínimo son dos semanas, puede ser más como menos dependiendo del cuadro.</p>
      <label for="tamano-finn">Tamaño:</label>
      <select id="tamano-finn">
        <option value="20x15">$10.000 - 20x15</option>
        <option value="20x20">$12.500 - 20x20</option>
        <option value="28x23">$14.000 - 28x23</option>
        <option value="30x20">$16.500 - 30x20</option>
        <option value="30x30">$18.000 - 30x30</option>
        <option value="35x25">$20.500 - 35x25</option>
      </select>
      <br>
      <button onclick="comprar('Finn y Jake Hora de aventura', 'tamano-finn')">Comprar por WhatsApp</button>
    </div>

    <!-- PRODUCTO: Hinata -->
    <div class="producto">
      <img src="Hinata.jpg" alt="Hinata Naruto">
      <h3>Hinata "Naruto"</h3>
      <p>Cada cuadro está hecho a mano desde 0, el tiempo de realización depende de los detalles y tamaños. El tiempo mínimo son dos semanas, puede ser más como menos dependiendo del cuadro.</p>
      <label for="tamano-hinata">Tamaño:</label>
      <select id="tamano-hinata">
        <option value="20x15">$10.000 - 20x15</option>
        <option value="20x20">$12.500 - 20x20</option>
        <option value="28x23">$14.000 - 28x23</option>
        <option value="30x20">$16.500 - 30x20</option>
        <option value="30x30">$18.000 - 30x30</option>
        <option value="35x25">$20.500 - 35x25</option>
      </select>
      <br>
      <button onclick="comprar('Hinata Naruto', 'tamano-hinata')">Comprar por WhatsApp</button>
    </div>

    <!-- PRODUCTO: Howl -->
    <div class="producto">
      <img src="Howl.jpg" alt="Howl El castillo ambulante">
      <h3>Howl "El castillo ambulante"</h3>
      <p>Cada cuadro está hecho a mano desde 0, el tiempo de realización depende de los detalles y tamaños. El tiempo mínimo son dos semanas, puede ser más como menos dependiendo del cuadro.</p>
      <label for="tamano-howl">Tamaño:</label>
      <select id="tamano-howl">
        <option value="20x15">$10.000 - 20x15</option>
        <option value="20x20">$12.500 - 20x20</option>
        <option value="28x23">$14.000 - 28x23</option>
        <option value="30x20">$16.500 - 30x20</option>
        <option value="30x30">$18.000 - 30x30</option>
        <option value="35x25">$20.500 - 35x25</option>
      </select>
      <br>
      <button onclick="comprar('Howl El castillo ambulante', 'tamano-howl')">Comprar por WhatsApp</button>
    </div>

    <!-- PRODUCTO: Otho Ai -->
    <div class="producto">
      <img src="Otho ai.jpg" alt="Otho Ai">
      <h3>Otho Ai "Wonder egg priority"</h3>
      <p>Cada cuadro está hecho a mano desde 0, el tiempo de realización depende de los detalles y tamaños. El tiempo mínimo son dos semanas, puede ser más como menos dependiendo del cuadro.</p>
      <label for="tamano-otho">Tamaño:</label>
      <select id="tamano-otho">
        <option value="20x15">$10.000 - 20x15</option>
        <option value="20x20">$12.500 - 20x20</option>
        <option value="28x23">$14.000 - 28x23</option>
        <option value="30x20">$16.500 - 30x20</option>
        <option value="30x30">$18.000 - 30x30</option>
        <option value="35x25">$20.500 - 35x25</option>
      </select>
      <br>
      <button onclick="comprar('Otho Ai Wonder egg priority', 'tamano-otho')">Comprar por WhatsApp</button>
    </div>

    <!-- PRODUCTO: Reki y Langa -->
    <div class="producto">
      <img src="Reki y Langa.jpg" alt="Reki y Langa">
      <h3>Reki y Langa "SK8"</h3>
      <p>Cada cuadro está hecho a mano desde 0, el tiempo de realización depende de los detalles y tamaños. El tiempo mínimo son dos semanas, puede ser más como menos dependiendo del cuadro.</p>
      <label for="tamano-reki">Tamaño:</label>
      <select id="tamano-reki">
        <option value="20x15">$10.000 - 20x15</option>
        <option value="20x20">$12.500 - 20x20</option>
        <option value="28x23">$14.000 - 28x23</option>
        <option value="30x20">$16.500 - 30x20</option>
        <option value="30x30">$18.000 - 30x30</option>
        <option value="35x25">$20.500 - 35x25</option>
      </select>
      <br>
      <button onclick="comprar('Reki y Langa SK8', 'tamano-reki')">Comprar por WhatsApp</button>
    </div>

    <!-- PRODUCTO: Rock Lee -->
    <div class="producto">
      <img src="Rock lee.jpg" alt="Rock Lee Naruto">
      <h3>Rock Lee "Naruto"</h3>
      <p>Cada cuadro está hecho a mano desde 0, el tiempo de realización depende de los detalles y tamaños. El tiempo mínimo son dos semanas, puede ser más como menos dependiendo del cuadro.</p>
      <label for="tamano-rock">Tamaño:</label>
      <select id="tamano-rock">
        <option value="20x15">$10.000 - 20x15</option>
        <option value="20x20">$12.500 - 20x20</option>
        <option value="28x23">$14.000 - 28x23</option>
        <option value="30x20">$16.500 - 30x20</option>
        <option value="30x30">$18.000 - 30x30</option>
        <option value="35x25">$20.500 - 35x25</option>
      </select>
      <br>
      <button onclick="comprar('Rock Lee Naruto', 'tamano-rock')">Comprar por WhatsApp</button>
    </div>

    <!-- PRODUCTO: The Promised Neverland -->
    <div class="producto">
      <img src="The promised neverland.jpg" alt="The Promised Neverland">
      <h3>The Promised Neverland</h3>
      <p>Cada cuadro está hecho a mano desde 0, el tiempo de realización depende de los detalles y tamaños. El tiempo mínimo son dos semanas, puede ser más como menos dependiendo del cuadro.</p>
      <label for="tamano-neverland">Tamaño:</label>
      <select id="tamano-neverland">
        <option value="20x15">$10.000 - 20x15</option>
        <option value="20x20">$12.500 - 20x20</option>
        <option value="28x23">$14.000 - 28x23</option>
        <option value="30x20">$16.500 - 30x20</option>
        <option value="30x30">$18.000 - 30x30</option>
        <option value="35x25">$20.500 - 35x25</option>
      </select>
      <br>
      <button onclick="comprar('The Promised Neverland', 'tamano-neverland')">Comprar por WhatsApp</button>
    </div>

    <!-- PRODUCTO: Zenitsu -->
    <div class="producto">
      <img src="Zenitsu.jpg" alt="Zenitsu Danger Kimetsu no Yaiba">
      <h3>Zenitsu Danger "Kimetsu no Yaiba"</h3>
      <p>Cada cuadro está hecho a mano desde 0, el tiempo de realización depende de los detalles y tamaños. El tiempo mínimo son dos semanas, puede ser más como menos dependiendo del cuadro.</p>
      <label for="tamano-zenitsu">Tamaño:</label>
      <select id="tamano-zenitsu">
        <option value="20x15">$10.000 - 20x15</option>
        <option value="20x20">$12.500 - 20x20</option>
        <option value="28x23">$14.000 - 28x23</option>
        <option value="30x20">$16.500 - 30x20</option>
        <option value="30x30">$18.000 - 30x30</option>
        <option value="35x25">$20.500 - 35x25</option>
      </select>
      <br>
      <button onclick="comprar('Zenitsu Danger Kimetsu no Yaiba', 'tamano-zenitsu')">Comprar por WhatsApp</button>
    </div>

  </section>

  <section id="contacto" style="text-align:center; padding: 20px;">
    <h2>Contacto</h2>
    <p>¿Querés una obra personalizada o tenés alguna consulta?</p>
    <p>Escribime a: <a href="mailto:nadine.anahi95@gmail.com">nadine.anahi95@gmail.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Taeidk - Todas las obras con amor 🎨💖</p>
  </footer>

  <script>
    function comprar(nombreProducto, idSelect) {
      const select = document.getElementById(idSelect);
      const tamano = select.value;
      const mensaje = `Hola, quisiera el ${nombreProducto} en ${tamano}`;
      const url = `https://wa.me/5491131457429?text=${encodeURIComponent(mensaje)}`;
      window.open(url, '_blank');
    }
  </script>

</body>
</html>
