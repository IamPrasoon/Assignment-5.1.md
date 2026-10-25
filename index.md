1. index.html


<!DOCTYPE html>
<html>
<head>
    <title>Styled Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>College Coding Club</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="registration.html">Register</a>
        <a href="contact.html">Contact</a>
    </nav>
    <h2>Welcome!</h2>
    <p>Learn coding and web development with us.</p>
</body>
</html>

2. style.css


body {
    background: lightblue;
    color: #222;
    font-family: Arial;
    text-align: center;
}
h1 {
    color: darkblue;
}
h2 {
    color: navy;
}
p {
    font-size: 18px;
}
nav {
    background: #333;
    padding: 15px;
}
a {
    color: white;
    text-decoration: none;
    margin: 10px;
}
a:hover {
    color: yellow;
}

Submission: Submit index.html and style.css, and inspect the styles using Chrome DevTools (F12 → Elements → Styles).