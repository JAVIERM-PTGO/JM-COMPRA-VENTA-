<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AutoMarket - Compra y Venta de Carros</title>
  <style>
    /* Estilos CSS */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
    }

    header {
      background-color: #222;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }

    nav {
      background-color: #444;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
      background: white;
      margin-top: 1rem;
      border-radius: 5px;
      box-shadow: 0 0 10px #ccc;
    }

    .car {
      border-bottom: 1px solid #ddd;
      padding: 1rem 0;
    }

    .car:last-child {
      border-bottom: none;
    }

    .promo {
      background-color: #e0ffe0;
      padding: 1rem;
      margin-top: 1rem;
      border-left: 5px solid green;
    }

    footer {
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    form input, form textarea, form button {
      display: block;
      width: 100%;
      margin: 0.5rem 0;
      padding: 0.7rem;
    }

    button {
      background-color: #28a745;
      color: white;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <!-- Encabezado -->
  <header>
    <h1>AutoMark
