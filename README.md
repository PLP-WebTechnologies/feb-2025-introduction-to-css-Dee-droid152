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
 - Improve readability and aesthetics./* General styles for body */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 20px;
    padding: 0;
}

/* Styling for headers */
h1 {
    color: #2c3e50;
    text-align: center;
    border-bottom: 3px solid #3498db;
    padding-bottom: 10px;
}

/* Styling for a class selector */
.card {
    background-color: white;
    padding: 20px;
    margin: 20px;
    border-radius: 8px;
    border: 1px solid #ddd;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

/* Styling for an ID selector */
#highlight {
    background-color: #ffeaa7;
    padding: 10px;
    font-weight: bold;
}

/* Styling for images */
img {
    width: 100%;
    max-width: 400px;
    display: block;
    margin: 0 auto;
    border: 3px solid #3498db;
    border-radius: 10px;
}

/* Button styling */
.button {
    background-color: #3498db;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    display: block;
    margin: 10px auto;
    text-align: center;
    font-size: 16px;
}

.button:hover {
    background-color: #2980b9;
}

   

Happy Coding! 💻✨
