<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>דוגמה לדף html</title>
        <style>
            body {
                direction: rtl;
                background-image: url(https://wallpapercave.com/wp/wp3758109.jpg);
                background-repeat:repeat-y;
                bacground-attachment: fixed;
                background-position-x: center;
                background-position-y: bottom;
                background-size: cover;
            }
            p {
                font-size: 12pt;
                color:aqua;
            }
            h1 {
                color: rgb(156, 162, 255);
                font-size: 24pt;
                text-align: center;
            }
            h2 {
                color: rgb(220, 138, 236);
                font-size: 20pt;
                text-align: justify;
            }
        </style>
    </head>
    <body>
        <h1>כותרת 1</h1>
        <h2>כותרת 2 ראשונה</h2>
        <p>
            פסקה לדוגמה שמדברת על מה שהצגנו בכותרת שהצגנו
        </p>
        <h2>כותרת 2 שניה</h2>
        <p style="direction: ltr; text-align: center;">
            second paragraph <br/> 
            for what we introduced in this header.
        </p>
    </body>
</html>