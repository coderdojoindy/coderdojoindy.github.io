<h1>Tutorial for coding game What is the Color of the Word?</h1>

In case you haven't seen the game, here's how to play: You're given a word. It's a color word, and the color the word is written in is different from what the word means. For example, you might see "Red" in blue letters.
The goal is to score points by guessing the color it's written in.

Let's start with the basic HTML framework:
```html
<!DOCTYPE html>
<html>
    <head>
        <script src=""></script>
        <style>
        
        </style>
        <script>
        
        </script>
    </head>
    <body>
        
    </body>
</html>
```

Now we can begin.
Let's first create the box that defines the game. The rest is background:
```html
    <body>
        <div id="game-container">
        
        </div>
    </body>
```

Of course, this will do nothing if we don't have proper stylesheets. Let's make the background color `#dddda0` (a dull yellow) and the game window 300x300 (definitely enough).
```html
        <style>
body {
    background-color: #dddda0;
}
.game-container {
    width: 300px;
    height: 300px;
    border: 2px solid black;
    /* centers the div */
    margin-left: auto;
    margin-right: auto;
}
        </style>
```



<h3>***** This tutorial is unfinished ***** </h3>
