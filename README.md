<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website Title</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="(link unavailable)">
    <link rel="preconnect" href="(link unavailable)" crossorigin>
    <link href="(link unavailable)" rel="stylesheet">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home" class="active">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h1>Welcome to Abdul Ramat Official Website</h1>
            <p>This is my sample website.</p>
            <button>Learn More</button>
        </section>
        <section id="about">
            <h1>About Us</h1>
            <p>My Name Is Ramat Isah Umar, From Bauchi State University Gadau Departmen of Mathematical Scince. 200Level Student .</p>
            <link rel="stylesheet" href="style.css">
    <style>
        .image-container {
            width: 200px;
            height: 200px;
            overflow: hidden;
            margin: 40px auto;
        }

        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            clip-path: inset(0 0 0 0);
            animation: cycle-crop 10s infinite;
        }

        @keyframes cycle-crop {
            0% {
                clip-path: inset(0 0 0 0);
            }
            25% {
                clip-path: inset(20% 0 0 0);
            }
            50% {
                clip-path: inset(0 20% 0 0);
            }
            75% {
                clip-path: inset(0 0 20% 0);
            }
            100% {
                clip-path: inset(0 0 0 20%);
            }
        }
    </style>
</head>
<body>
    <div class="image-container">
        <img src="me.jpg" alt="student profile">
    </div><img src="mejpg" alt="Ramat Isah Umar Matric pic" width="190" height="200" >
        </section>
        <section id="contact">
            <h1>Get in Touch</h1>
            <p>This is the contact section.</p>
            <form>
                <input type="text" placeholder="Name">
                <input type="email" placeholder="Email">
                <textarea placeholder="Message"></textarea>
                <button><a href="#">Send</a></button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Your Website</p>
        <ul>
            <li><a href="#"><i class="fa fa-facebook"></i></a></li>
            <li><a href="#"><i class="fa fa-twitter"></i></a></li>
            <li><a href="#"><i class="fa fa-instagram"></i></a></li>
        </ul>
    </footer>
    <script src="script.js"></script>
</body>
</html>
