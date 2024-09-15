## project first -- 
{<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <link rel="stylesheet" href="style.css" />
    <link rel="stylesheet" href="../styles.css" />
    <title>JavaScript Background Color Switcher</title>
  </head>
  <body>
    <nav>
      <a href="/" aria-current="page">Home</a>
      <a target="_blank" href="https://www.youtube.com/@chaiaurcode"
        >Youtube channel</a
      >
    </nav>
    <div class="canvas">
      <!-- <a
        style="
          background-color: #fff;
          padding: 10px 30px;
          border-radius: 8px;
          color: #212121;
          text-decoration: none;
          border: 2px solid #212121;
        "
        href="../index.html"
        >Back to Home Page</a
      > -->
      <h1>Color Scheme Switcher</h1>
      <span class="button" id="grey"></span>
      <span class="button" id="white"></span>
      <span class="button" id="blue"></span>
      <span class="button" id="yellow"></span>
      <h2>
        Try clicking on one of the colors above
        <span>to change the background color of this page!</span>
      </h2>
    </div>
    <script src="chaiaurcode.js"></script>
  </body>
</html>
,{let buttons =document.querySelectorAll(".button");
const boody= document.querySelector("body");
const h1= document.querySelector("h1");

buttons.forEach(function(button){
  console.log(buttons)
  button.addEventListener('click',function(e){
    console.log(e.target);
    if (e.target.id === 'grey'){
      boody.style.backgroundColor = e.target.id;
      h1.innerHTML=`Color Scheme Switcher to ${e.target.id}`;
    }
    if (e.target.id === 'white'){
      boody.style.backgroundColor = e.target.id;
      h1.innerHTML=`Color Scheme Switcher to ${e.target.id}`;
    }
    if (e.target.id === 'blue'){
      boody.style.backgroundColor = e.target.id;
      h1.innerHTML=`Color Scheme Switcher to ${e.target.id}`;
    }
    if (e.target.id === 'yellow'){
      boody.style.backgroundColor = e.target.id;
      h1.innerHTML=`Color Scheme Switcher to ${e.target.id}`;
    }
  })

})
}}