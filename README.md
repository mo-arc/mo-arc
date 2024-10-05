<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coordinate & Title Assignment</title>
</head>
<body>
    <h1>Enter Coordinates and Title</h1>
    <form action="/submit" method="POST">
        <label for="x-coord">X Coordinate:</label>
        <input type="number" id="x-coord" name="x" required><br><br>

        <label for="y-coord">Y Coordinate:</label>
        <input type="number" id="y-coord" name="y" required><br><br>

        <label for="title">Title:</label>
        <input type="text" id="title" name="title" required><br><br>

        <button type="submit">Submit</button>
    </form>
</body>
</html>
