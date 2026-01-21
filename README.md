# JLuo527.github.io
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>Meine persönliche Website</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        /* Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            height: 100vh;
            background-image: url("https://images.unsplash.com/photo-1501785888041-af3ef285b470");
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            color: white;
        }

        /* Dark overlay for better readability */
        .overlay {
            background: rgba(0, 0, 0, 0.55);
            height: 100%;
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 20px;
        }

        .container {
            max-width: 700px;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 15px;
        }

        h2 {
            font-weight: 300;
            margin-bottom: 25px;
        }

        p {
            font-size: 1.1rem;
            line-height: 1.6;
            margin-bottom: 30px;
        }

        .button {
            display: inline-block;
            padding: 12px 30px;
            border: 2px solid white;
            color: white;
            text-decoration: none;
            border-radius: 30px;
            transition: all 0.3s ease;
        }

        .button:hover {
            background: white;
            color: black;
        }

        footer {
            position: absolute;
            bottom: 15px;
            width: 100%;
            text-align: center;
            font-size: 0.9rem;
            opacity: 0.8;
        }
        p{
            color: blanchedalmond;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            font-size: 0,15cm;
        }
        a{
            color: rgb(177, 113, 17);
        }
    </style>
</head>
<body>

    <div class="overlay">
        <div class="container">
            <h1>Yangjie Luo</h1>
            <h2><a href="http://127.0.0.1:5500/bio.html">Biography</a></h2>

            <p>
                I’m a student with a strong interest in learning, technology, and problem-solving.
                I enjoy exploring new ideas and building skills through projects and collaboration.
                This website showcases my achivements, projects, and interests as I continue to grow
                both academically and personally.
            </p>

            <a href="http://127.0.0.1:5500/contact_me.html" class="button">Contact Me</a>
        </div>
    </div>

    <footer>
        © 2026 Yangjie Luo - All rights reserved.
    </footer>

</body>
</html>
