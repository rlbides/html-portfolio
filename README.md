# htmp-portfolio

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercise 11</title>
    <style>
        * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
          scroll-behavior: smooth;
          /* border: 0.5px dotted green; */
          color: rgb(0, 0, 0);
        }
        
        html {
          font-size: 62.5%;
        }
        
        ul,
        ol {
          list-style: none;
        }
        
        a {
          text-decoration: none;
        }
        
        body {
            font-size: 1.6rem;
            overflow-wrap: break-word;
            text-wrap: pretty;
            hyphens: auto;
            font-family: "Merriweather", serif;
            line-height: 1.5;
            background-color: #C1E0FF;
        }
        
        /* wrap all of the content inside the body to a div with a class of "site" */
        .site {
            min-height: 100dvh;
            display: grid;
            grid-template-rows: auto 1fr auto;
            grid-template-columns: minmax(0, 1fr);
        }

        header nav ul {
            display: flex;
            gap: 1rem;
            margin-top: 1em;
            margin-left: 1em;
        }

        header nav ul a{
            transition: all 333ms ease;
        }

        header nav ul a:hover{
            color: rgb(98, 0, 255);
            font-size: 1.1em;
            text-decoration: underline;
        }

        hr {
            border: .001em solid #000000;
            max-width: 99%;
            margin: 1em auto;
        }

        div {
            margin-left: 1em;
            display: flex;
            flex-direction: row;
        }

        picture{
            border-radius: 50%;
            border: .35rem dashed rgb(59, 35, 82);
        }

        picture img{
            border-radius: 50%;
            width: 100%;
            height: 100%;
        }
        
        div h1{
            margin-bottom: .2em;
        }


        .description {
            display: flex;
            flex-direction: column;
            max-width: 60ch;
        }
    </style>
</head>
<body>
    <div class="site">
        <header>
            <nav>
                <ul>
                    <li><a href="https://drive.google.com/drive/folders/1p-4-hyBrRoqzNjc7XPjVH2hMfhjW5JqF?usp=drive_link">Home</a></li>|
                    <li><a href="https://drive.google.com/file/d/1E9qR75VP1g0rhgF-sg2_xameqwN9DBIy/view?usp=drive_link">Exercises</a></li>|
                    <li><a href="https://drive.google.com/drive/folders/1EJHv89ZlFDPn1JJWKW5wHZxQNRwmRffJ?usp=drive_link">Designs</a></li>|
                    <li><a href="https://www.facebook.com/">Facebook</a></li>
                </ul>
            </nav>
            <hr>
        </header>
        <main>
            <div>
                <picture>
                    <img src="/ralph-lionel-bides.jpg" alt="self-portrait">
                </picture>
                <div class="description">
                    <h1>Ralph Lionel Bides</h1>
                        <h3>
                            Rising third year student at Filamer Christian University taking up Bachelor of Science in Information Technology with
                            career interests in website development.
                        </h3>
                </div>
            </div>
        </main>
    </div>
</body>
</html>
