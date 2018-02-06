# SGA0.2
<!DOCTYPE html>
<head>
  <link href="/normalize.css" rel="stylesheet">
  <style>
    body {
      font-family: helvetica;
    }
    header {
      text-align: center;
      background: url('https://i.imgur.com/zfSTsmg.jpg');
      background-size: cover;
      color: white;
    }
    a {
      color: white;
    }
    h1 {
      font-size: 70px;
    }
    img {
      margin: 40px 0px 0px 0px;
      border: 7px solid white;
      border-radius: 20px;
    }
    ul {
      padding: 20px;
      background: rgba(0,0,0,0.8);
    }
    li {
      display: inline;
      padding: 0px 10px 0px 10px;
    }
    article {
      max-width: 500px;
      padding: 20px;
      margin: 0 auto;
    }
    @media (max-width: 500px) {
      h1 {
        font-size: 36px;
        padding: 5px;
      }
      li {
        padding: 5px;
        display: block;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://i.imgur.com/0y6TZM5.jpg?1">
    <h1>Oluwatobi's Blog</h1>
    <ul>
      <li><a href="#">About Me</a></li>
      <li><a href="#">Urban Meteorology</a></li>
      <li><a href="#">UI/UX</a></li>
    </ul>
  </header>
  <article>
    <h2>Urban Environments</h2>
    <p>The heterogeneous nature of urban environments means that atmospheric research ideally requires a dense network of sensors to adequately resolve the local climate. With recent advances in sensor technology, a number of urban meteorological networks now exist with a range of research or operational objectives.</p>
    <button>Like</button>
  </article>
  <article>
    <h2>Meso scale sensors</h2>
    <p>Meso-scale networks observe regional atmospheric processes and weather phenomenon such as thunderstorms and squall lines – such processes are often hazardous, but cannot be adequately captured by individual monitoring stations, particularly over urban environments (Oke, 2004). Meso-scale networks potentially extend over hundreds to hundreds of thousands of square kilometres, covering both urbanized, peri-urban and rural areas.</p>
    <button>Like</button>
  </article>
  <article>
    <h2>Getting Started in UX Design</h2>
    <p>Although user experience (UX) is quite new, designing user experience is not. For as long as there have been people, there have been products; for as long as there have been products, there have been users; and for as long as there have been users, there has been user experience. In this sense, all design is user experience design.</p>
    <button>Like</button>
  </article>
  <script>
    $("button").on("click", function() {
      alert("Clicked!");
    });
  </script>
</body>
