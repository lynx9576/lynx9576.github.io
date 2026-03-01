<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Name</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    height: 100vh;
    font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", Arial, sans-serif;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    background: url('background.jpg') no-repeat center center/cover;
}

.container {
    background: rgba(0,0,0,0.4);
    padding: 60px;
}

h1 {
    font-size: 48px;
    font-weight: 500;
    margin-bottom: 20px;
}

p {
    margin-bottom: 40px;
    font-size: 18px;
    opacity: 0.85;
}

a {
    display: block;
    margin: 12px 0;
    font-size: 20px;
    color: white;
    text-decoration: none;
    transition: opacity 0.3s;
}

a:hover {
    opacity: 0.6;
}
</style>
</head>

<body>

<div class="container">
    <h1>Your Name</h1>
    <p>A short introduction about yourself.</p>

    <a href="profile.html">Profile</a>
    <a href="research.html">Research</a>
    <a href="blog.html">Blog</a>
    <a href="contact.html">Contact</a>
</div>

</body>
</html>
