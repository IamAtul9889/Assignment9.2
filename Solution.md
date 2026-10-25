```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Article</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f1f5f9;
            line-height: 1.7;
            font-size: 1rem;
        }

        header {
            background: #1e293b;
            color: white;
            text-align: center;
            padding: 1.5rem;
        }

        .container {
            max-width: 900px;
            margin: auto;
            padding: 1.5rem;
            background: white;
        }

        h1 {
            font-size: clamp(1.8rem, 4vw, 2.8rem);
        }

        h2 {
            font-size: clamp(1.4rem, 3vw, 2rem);
        }

        p {
            font-size: 1.1rem;
            margin-bottom: 1.2rem;
        }

        img {
            display: block;
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 20px auto;
        }

        @media (max-width: 600px) {
            .container {
                padding: 1rem;
            }

            p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>My Portfolio</h1>
    <p>Welcome to my webpage</p>
</header>

<div class="container">
    <h2>About Technology</h2>

    <img src="https://picsum.photos/id/0/900/400"
         alt="Laptop on a desk">

    <p>
        Technology plays an important role in our daily lives.
        It helps us learn new skills, communicate with people,
        and complete tasks more efficiently.
    </p>

    <h2>My Learning Journey</h2>

    <img src="https://picsum.photos/id/20/900/400"
         alt="Computer and technology">

    <p>
        I am learning HTML and CSS to build responsive websites.
        Responsive design makes a webpage look good on mobile,
        tablet, and desktop screens.
    </p>
</div>

</body>
</html>
```