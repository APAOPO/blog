<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>蒸氣龐克風首頁</title>
  <link href="https://fonts.googleapis.com/css2?family=UnifrakturCook:wght@700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <style>
    body {
      margin: 0;
      font-family: 'UnifrakturCook', cursive;
      background: linear-gradient(#3b2f2f, #1e1a1a);
      color: #d2b48c;
    }

    header {
      background-color: #4b3e2e;
      padding: 1rem;
      text-align: center;
      border-bottom: 5px solid #8b6f47;
    }

    header h1 {
      font-size: 3rem;
      color: #f0e68c;
      margin: 0;
    }

    .container {
      padding: 2rem;
      text-align: center;
    }

    .gear {
      font-size: 3rem;
      color: #c0a16b;
      margin: 1rem;
      animation: rotate 10s linear infinite;
    }

    @keyframes rotate {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #2d2424;
      border-top: 3px solid #8b6f47;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1><i class="fas fa-cogs"></i> 蒸氣龐克之門 <i class="fas fa-cogs"></i></h1>
  </header>

  <div class="container">
    <p>歡迎進入蒸氣與黃銅交織的未來世界。</p>
    <div>
      <i class="fas fa-cog gear"></i>
      <i class="fas fa-cog gear" style="animation-direction: reverse;"></i>
    </div>
  </div>

  <footer>
    &copy; 2025 蒸氣工作坊. 保留所有權利。
  </footer>
</body>
</html>
