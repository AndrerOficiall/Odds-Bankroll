<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Página de Download</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f3f3f3;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
    }

    .container {
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
    }

    h1 {
      color: #333;
    }

    a.download-btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 25px;
      background: #007BFF;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-size: 16px;
      transition: background 0.3s ease;
    }

    a.download-btn:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Download do Arquivo</h1>
    <p>Clique no botão abaixo para baixar o arquivo.</p>
    <a class="download-btn" href="seu-arquivo.zip" download>Baixar Agora</a>
  </div>
</body>
</html>
