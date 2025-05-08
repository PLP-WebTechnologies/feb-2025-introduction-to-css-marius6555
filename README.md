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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Styled Page</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1 id="main-title">Welcome to My Styled Page</h1>
  <p class="intro-text">hello world am marius tech enthuist.</p>

  <img src="https://via.placeholder.com/300" alt="Sample Image" class="styled-image" />

  <div class="box">
    <p>i love codding.</p>
  </div>
</body>
</html>
/* ID selector */
#main-title {
  color: #2c3e50;
  font-family: 'Georgia', serif;
  text-align: center;
  margin-top: 20px;
}

/* Class selector */
.intro-text {
  color: #34495e;
  font-family: 'Arial', sans-serif;
  font-size: 18px;
  margin: 20px;
  line-height: 1.6;
}

/* Element selector */
body {
  background-color: #f4f4f4;
  padding: 20px;
}

/* Image styling */
.styled-image {
  display: block;
  margin: 30px auto;
  border: 5px solid #3498db;
  padding: 10px;
  border-radius: 10px;
  max-width: 100%;
}

/* Box with margin, padding & border */
.box {
  border: 2px dashed #8e44ad;
  padding: 20px;
  margin: 20px auto;
  max-width: 600px;
  background-color: #ffffff;
}


Happy Coding! 💻✨
