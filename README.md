<!DOCTYPE HTML>

<html lang='pt-br'>
    <head>
        <title>CSS_01</title>
        <meta name='author' content='julio pablo'>
        <meta name='description' content="simple css and html">
        <meta name='keywords' content="basic css, basic html">
        <meta charset="utf-8">
        <style>
            body {
                font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
                background-color: #ccc;
            }

            #container {
                margin: auto;
                background-color: rgb(163, 163, 163);
                width: 80%;
                height: 600px;
            }

            #cssTitulo {
                color: rgb(255, 255, 255);
                text-shadow: rgb(0, 0, 0) 5px 5px 5px;
                padding: 0px;
                background-color: rgb(88, 88, 88);
                text-align: center;
                font-size: 80px;
            }

            #container p {
                padding-top: 150px;
                font-size: 35px;
                text-align: center;
                text-shadow: rgb(122, 122, 122) 1px 1px 1px;
            }

            #container strong {
                font-size: 100px;
                color: rgb(255, 255, 255);
                text-shadow: rgb(0, 0, 0) 3px 3px 3px;
            }
        </style>
    </head>

    <body>
        <div id='container'>
            <h1 id='cssTitulo'>css</h1>
            <p>and <strong>HTML</strong></p>
        </div>
    </body>
</html>
