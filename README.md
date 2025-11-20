A simple JavaScript project that switches a light bulb ON and OFF using two buttons.

# Features

Click ON button → bulb image changes to glowing bulb

Click OFF button → bulb image returns to off state

Uses basic HTML, CSS, and JavaScript

Beginner-friendly project for learning DOM manipulation
#index.html:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta-name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bulb Switch</title>
</head>
<body>
    <h1 id="heading">Switch Game</h1>
    <img src="https://cdn3.vectorstock.com/i/1000x1000/89/72/object-bulb-off-vector-1858972.jpg" id="bulbimage" />
    
    <button id="onclickbutton" onclick="onClick()">on</button>
    <button id="offclickbutton" onclick="offClick()">off</button>

    <script src="index.js"></script>
</body>
</html> 
#index.js:
function onClick() {
    let bulb = document.getElementById("bulbimage");
    bulb.src = "https://cdn2.vectorstock.com/i/1000x1000/89/73/object-bulb-on-vector-1858973.jpg";
}

function offClick() {
    let bulb = document.getElementById("bulbimage");
    bulb.src = "https://cdn3.vectorstock.com/i/1000x1000/89/72/object-bulb-off-vector-1858972.jpg";
}
#Technologies Used

HTML

CSS

JavaScript
