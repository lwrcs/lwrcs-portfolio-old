---
layout: default
title: Portfolio
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }}</title>
    <link rel="stylesheet" href="/assets/css/style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
            display: flex;
            min-height: 100vh;
            justify-content: center;
        }
        header {
            margin-bottom: 30px;
        }
        main {
            max-width: 800px;
        }
        .project {
            margin-bottom: 50px;
            position: relative;
            display: inline-block;
        }
        .project img {
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            transition: opacity 0.9s ease;
        }
        .project:hover img {
            opacity: 0.7;
        }
        .project .overlay { 
            border-radius: 10px;
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        .project:hover .overlay {
            opacity: 1;
        }
        .project h2 {
            font-size: 24px;
            margin-bottom: 10px;
            color: #fff;
        }
        .project p {
            color: #ccc;
        }
        footer {
            margin-top: 50px;
            color: #666;
        }
    </style>
</head>
<body>

<header>
    <h1>{{ page.title }}</h1>
</header>

<main>
    <section class="project">
        <a href="https://www.youtube.com/watch?v=Pz2oktl1Hnw">
            <img src="/assets/images/rusrs.jpg" alt="Project 1">
            <div class="overlay">
                <h2>"r u srs?" Music Video</h2>
                <p>Filming, Editing, 3D Title Animation</p>
            </div>
        </a>
    </section>
    <section class="project">
        <a href="/project2.html">
            <img src="/assets/images/project2.jpg" alt="Project 2">
            <div class="overlay">
                <h2>Project 2</h2>
                <p>Description of Project 2 goes here.</p>
            </div>
        </a>
    </section>
    <section class="project">
        <a href="/project3.html">
            <img src="/assets/images/project3.jpg" alt="Project 3">
            <div class="overlay">
                <h2>Project 3</h2>
                <p>Description of Project 3 goes here.</p>
            </div>
        </a>
    </section>
</main>

<footer>
    <p>&copy; 2024 Your Name</p>
</footer>

</body>
</html>
