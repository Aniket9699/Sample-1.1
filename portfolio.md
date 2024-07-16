<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>John Doe - Frontend Developer</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
<body>
    <main>
        <section class="intro">
            <img src="profile.png" alt="John Doe" class="profile-pic">
            <div class="intro-text">
                <h1>Hello, I'm <br><span>Aniket Kakde</span></h1>
                <h2>DevOps Engineer</h2>
                <div class="social-icons">
                    <a href="https://linkedin.com/in/johndoe" target="_blank"><img src="linkedin.png" alt="LinkedIn"></a>
                    <a href="https://github.com/johndoe" target="_blank"><img src="github.png" alt="GitHub"></a>
                    <a href="https://linkedin.com/in/johndoe" target="_blank"><img src="email.png" alt="Email"></a>
                </div>
            </div>
        </section>
    </main>
</body>
</html>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #fff;
    color: #333;
}

header {
    background-color: #fff;
    padding: 10px 0;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-size: 18px;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 90vh;
}

.intro {
    text-align: center;
}

.profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 20px;
}

.intro-text h1 {
    font-size: 36px;
    margin-bottom: 10px;
}

.intro-text h1 span {
    font-size: 48px;
    color: #000;
}

.intro-text h2 {
    font-size: 24px;
    margin-bottom: 20px;
}

.buttons {
    margin-bottom: 20px;
}

.btn {
    text-decoration: none;
    color: #fff;
    background-color: #333;
    padding: 10px 20px;
    margin: 0 10px;
    border-radius: 5px;
}

.social-icons a {
    margin: 0 10px;
}

.social-icons img {
    width: 30px;
    height: 30px;
}
</style>