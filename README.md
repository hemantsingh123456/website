# website
mywebsite
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Static Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Static Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="home">
        <h2>Home</h2>
        <p>This is the homepage of my static website.</p>
    </section>
    <section id="about">
        <h2>About</h2>
        <p>This section contains information about the website.</p>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>You can contact me via email at <a href="mailto:example@example.com">example@example.com</a>.</p>
    </section>
    <footer>
        <p>&copy; 2024 My Static Website</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav {
    background-color: #444;
    color: white;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: white;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

3. JavaScript File (script.js)

javascript

document.addEventListener('DOMContentLoaded', function () {
    console.log("Welcome to My Static Website!");
    // Add any interactive functionality here
});
