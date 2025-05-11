<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KOROKOY</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0f0f0f;
            color: #ffffff;
            margin: 0;
            padding: 0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .container {
            text-align: center;
            padding: 2rem;
            margin-top: 10vh;
        }

        h1 {
            font-size: 4rem;
            margin-bottom: 3rem;
            letter-spacing: 4px;
            text-transform: uppercase;
        }

        .nav-links {
            list-style: none;
            padding: 0;
        }

        .nav-links li {
            margin: 1.5rem 0;
        }

        .nav-links a {
            color: #ffffff;
            text-decoration: none;
            font-size: 1.4rem;
            transition: color 0.3s ease;
        }

        .nav-links a:hover {
            color: #00ff88;
            text-decoration: underline;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            
            .nav-links a {
                font-size: 1.2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>KOROKOY</h1>
        <nav>
            <ul class="nav-links">
                <li><a href="#about">about</a></li>
                <li><a href="#how-to-buy">how to buy</a></li>
                <li><a href="#tokenomics">tokenomics</a></li>
                <li><a href="#roadmap">roadmap</a></li>
                <li><a href="#contact">contact</a></li>
            </ul>
        </nav>
    </div>
</body>
</html>
