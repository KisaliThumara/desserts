<!-- index.html -->

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Delicious Pudding Recipes</title>
    <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }

    header {
      background-color: #008b8b;
      background-image:url("https://th.bing.com/th/id/OIP.i0s9iyIeDPlTa9lB-Z21zgAAAA?rs=1&pid=ImgDetMain");
      color: black;
      text-align: center;
      padding: 5em;
    }

    nav {
      display: flex;
      justify-content: space-around;
      background-color: #89ACFF;
      padding: 0.5em;
    }

    section {
      padding: 20px;
    }
    
    * {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

.row::after {
  content: "";
  clear: both;
  display: table;
}

    .recipe {
      border: 1px solid #ddd;
      margin: 10px;
      padding: 10px;
      background-color: #fff;
      border-radius: 5px;
      overflow: hidden;
    }
  </style>
</head>

<body>
  <header>
     <h1>Delicious Pudding Recipes</h1>
    <p>Your go-to place for mouth-watering desserts</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#catalog">Recipe Catalog</a>
    <a href="#contact">Contact Us</a>
  </nav>

  <section id="home">
     <h2>Welcome to Delicious Pudding Recipes!</h2>
    <p>Explore a variety of delicious puddings and learn how to make them at home.</p>
   <div class="row">
  <div class="column">
    <img src="https://3.bp.blogspot.com/-1KZ0aoHPpmE/XAJl6KMkHSI/AAAAAAAAJe4/eOZ11EbhDro_2p8lJWkVwU5MK2UsFFVOgCKgBGAs/s1600/D3E63010-84F5-4B0B-8617-7639F12036F9.jpg" alt="Snow" style="width:100%">
  </div>
  <div class="column">
    <img src="https://th.bing.com/th/id/OIP.yMNBZw6NxveQtG8xuQMeyAHaEK?rs=1&pid=ImgDetMain" alt="Forest" style="width:100%">
  </div>
  <div class="column">
    <img src="https://th.bing.com/th/id/R.1fc82e24fa03d47b88853c95986912c9?rik=v8NToN%2fgskP0RQ&pid=ImgRaw&r=0" alt="Mountains" style="width:100%">
  </div>
  </section>

  <footer>
    <p>&copy; 2023 Delicious Recipes</p>
  </footer>
</body>
</html>
