# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.
 - <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Styling Example</title>
    <!-- Link to External CSS File -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header class="header">
        <h1>Welcome to My Stylish Website</h1>
    </header>

    <section class="content">
        <h2>About Us</h2>
        <p>We create beautiful and user-friendly websites. Here is an example of an image styled with CSS:</p>
        <img src="https://via.placeholder.com/300" alt="Example Image" class="styled-image">
    </section>

    <footer class="footer">
        <p>&copy; 2025 Stylish Website</p>
    </footer>

</body>
</html>
/* Universal selector to set padding and margin for all elements */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Class selector to style header */
.header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
    font-family: 'Arial', sans-serif;
}

/* Class selector to style content section */
.content {
    padding: 30px;
    margin: 20px;
    background-color: #f4f4f4;
    border: 2px solid #ccc;
}

/* Element selector to style the footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    font-family: 'Courier New', Courier, monospace;
}

/* Style the image with padding, border, and margin */
.styled-image {
    display: block;
    margin: 20px auto;
    padding: 10px;
    border: 5px solid #ddd;
    border-radius: 8px;
    max-width: 100%;
    height: auto;
}

/* Change the font for paragraphs */
p {
    font-family: 'Verdana', sans-serif;
    line-height: 1.6;
}


Happy Coding! 💻✨
