# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>This is the home section of the website.</p>
        </section>
        <section id="about">
            <h2>About</h2>
            <p>This is the about section of the website.</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>This is the contact section of the website.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 My Website</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 1rem;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
    position: fixed;
    width: 100%;
    bottom: 0;
}document.addEventListener('DOMContentLoaded', function() {
    console.log('Website is loaded and ready.');
});
