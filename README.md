# githupagetest
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mapa Conceptual - Construcción de Software</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      padding: 20px;
    }

    .mapa {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .nodo {
      background-color: #ffffff;
      border: 2px solid #4CAF50;
      border-radius: 10px;
      padding: 10px 20px;
      margin: 10px;
      text-align: center;
      font-weight: bold;
      width: fit-content;
    }

    .linea {
      height: 20px;
      border-left: 2px solid #4CAF50;
      margin: 0 auto;
    }

    .fila {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    .nodo-grande {
      font-size: 1.2em;
      background-color: #e8f5e9;
    }
  </style>
</head>
<body>
  <h1>Mapa Conceptual: Construcción de Software</h1>
  <div class="mapa">

    <div class="nodo nodo-grande">Construcción de Software</div>
    <div class="linea"></div>

    <div class="fila">
      <div class="nodo">Diseño</div>
      <div class="nodo">Codificación</div>
      <div class="nodo">Pruebas</div>
      <div class="nodo">Mantenimiento</div>
    </div>

    <div class="linea"></div>

    <div class="fila">
      <div class="nodo">Diseño Arquitectónico</div>
      <div class="nodo">Lenguajes de Programación</div>
      <div class="nodo">Pruebas Unitarias</div>
      <div class="nodo">Corrección de Errores</div>
    </div>

    <div class="linea"></div>

    <div class="fila">
      <div class="nodo">Modelado UML</div>
      <div class="nodo">Control de Versiones</div>
      <div class="nodo">Pruebas de Integración</div>
