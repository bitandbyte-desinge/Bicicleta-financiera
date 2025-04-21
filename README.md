<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bicicleta Financiera</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Bicicleta Financiera</h1>
    <p>Cotización del dólar y comparador de plazos fijos</p>
  </header>

  <section id="dolar">
    <h2>Cotización del Dólar (Tiempo real)</h2>
    <div id="cotizacion">Cargando...</div>
  </section>

  <section id="simulador">
    <h2>Simulador</h2>
    <label>Monto: <input type="number" id="monto" value="1000000"></label>
    <button onclick="simular()">Simular</button>
    <p id="resultado"></p>
  </section>

  <script src="script.js"></script>
</body>
</html>
