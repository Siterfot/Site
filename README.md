<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Constructor</title>
</head>
<body>
    <h1>Website Constructor</h1>
    
    <form action="/add_block" method="post">
        <label for="block_content">Block Content:</label>
        <input type="text" id="block_content" name="block_content" required>
        <button type="submit">Add Block</button>
    </form>

    <h2>Blocks:</h2>
    {% for block in blocks %}
        <p>{{ block }}</p>
    {% endfor %}
</body>
</html>
# Site
Bilder site
