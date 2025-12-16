<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>The New York Times</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header class="top-bar">
    <h1>The New York Times</h1>
    <p>Wednesday, October 20, 2025</p>
</header>

<nav class="menu">
    <a href="#">World</a>
    <a href="#">Politics</a>
    <a href="#">Business</a>
    <a href="#">Technology</a>
    <a href="#">Science</a>
    <a href="#">Health</a>
    <a href="#">Arts</a>
</nav>

<main class="content">
    <section class="lead">
        <h2>Main Headline Goes Here</h2>
        <p>
            This section represents the primary news headline,
            similar to the New York Times homepage layout.
        </p>
    </section>

    <section class="grid">
        <article>
            <h3>Article Title One</h3>
            <p>Short description of the article.</p>
        </article>

        <article>
            <h3>Article Title Two</h3>
            <p>Short description of the article.</p>
        </article>

        <article>
            <h3>Article Title Three</h3>
            <p>Short description of the article.</p>
        </article>
    </section>
</main>

<footer>
    <p>© 2025 The New York Times Company</p>
</footer>

</body>
</html>
body {
    margin: 0;
    font-family: Georgia, "Times New Roman", serif;
    background-color: #f5f5f5;
}

.top-bar {
    text-align: center;
    padding: 15px;
    border-bottom: 1px solid black;
    background-color: white;
}

.menu {
    display: flex;
    justify-content: center;
    border-bottom: 1px solid #ddd;
    background-color: white;
}

.menu a {
    padding: 10px 15px;
    text-decoration: none;
    color: black;
    font-weight: bold;
}

.menu a:hover {
    background-color: #eee;
}

.content {
    width: 80%;
    margin: auto;
    padding: 20px;
}

.lead {
    border-bottom: 1px solid #ccc;
    margin-bottom: 20px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
}

article {
    background-color: white;
    padding: 10px;
    border: 1px solid #ddd;
}

footer {
    text-align: center;
    padding: 15px;
    background-color: white;
    border-top: 1px solid #ddd;
}
