# Cobra's World

This is a simple snake game built with HTML, CSS, and JavaScript. The game is controlled by the arrow keys, and the objective is to eat as much food as possible without hitting the walls or your own tail.

## How to play

To play the game, simply open the `index.html` file in a web browser. The game will start automatically. Use the arrow keys to control the snake. The snake will move in the direction of the last arrow key that was pressed.

If the snake eats a piece of food, it will grow longer. The game ends if the snake hits the walls or its own tail.

## Code explanation

The code for the game is divided into three files:

* `index.html`: This file contains the HTML code for the game. It includes the game board, the score, and the high score.
* `index.js`: This file contains the JavaScript code for the game. It controls the movement of the snake, the food, and the score.
* `style.css`: This file contains the CSS code for the game. It styles the game board, the snake, and the food.

### index.html

The `index.html` file contains the following code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cobra's world</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="body">
        <div id="scoreBox">Score : 0</div>
        <div id="hiscoreBox">High Score : 0</div>
        <div id="board"></div>
    </div>
</body>
<script src="index.js"></script>
</html>
```

The `<head>` section of the file contains the title of the game, the viewport meta tag, and a link to the CSS file. The `<body>` section of the file contains the game board, the score, and the high score. The game board is a `<div>` element with the ID of `board`. The score is a `<div>` element with the ID of `scoreBox`.
