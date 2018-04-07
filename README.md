# theSandbox
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Section 3: How JavaScript Works Behind the Scenes</title>
    </head>

    <body>
        <h1>Section 3: How JavaScript Works Behind the Scenes</h1>
        <script src="tetris.js"></script>
    </body>
</html>
const canvas = document.ggetElementByID('tetris');
const context = canvas.getContext('2');

context.fillStlye = '#000';
context.fillRect(0, 0, canvas.width, canvas.height);
