<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Picture This!</title>
  <link rel="stylesheet" href="main.css">
</head>

<body>
  <header class="header">
    <div class="title">
      <h1>Picture This!</h1>
      <h2>My Really Cool Blog Post</h2>
      <img src="c:\Users\simranjot\Downloads\museum.jpg" alt="museum">
    </div>
    <picture>
        <source media="(max-width: 959px)" srcset="./image/sunset.jpg">
        <source media="(min-width: 960px)" srcset="./image/sunset.jpg">
        
    </picture>
  </header>
</body>

</html>
