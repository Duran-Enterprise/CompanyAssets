# Typography

## Table of Contents

- [Typography](#typography)
  - [Table of Contents](#table-of-contents)
  - [Typography Template](#typography-template)
  - [Usage Instructions](#usage-instructions)

## Typography Template
This template showcases typography using the "Noto Sans" font family, which is chosen for its readability and versatility.

## Usage Instructions

1. You can click [here](src/templates/default.html) to view the template. The font family used for this typography template is ["Noto Sans" from Google Fonts](https://fonts.google.com/noto/specimen/Noto+Sans).


2. Import the google font using either of the following blocks of code to use the font. Paste it inside your html's `<head>` section
    ```html
    <!-- You can use this -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">

    <!-- or this -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
    </style>
    ```

    ```css
    /* If you prefer to use pure external css, you can import the font using this at the top of your external css file*/
    @import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap'); 

    ```
    
3. Apply the font on the website using the css code:
   ```css
   :root{
    --font-family: 'Noto Sans', sans-serif;
   }
   ```
