<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Johnny Mitchell - Voice Acting Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background: #2c3e50;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
            margin: 0.5rem 0;
        }
        nav {
            margin-top: 1rem;
        }
        nav a {
            color: #1abc9c;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 1rem;
        }
        section {
            margin-bottom: 3rem;
        }
        .demos audio {
            width: 100%;
            margin-top: 1rem;
        }
        .about {
            background: #ecf0f1;
            padding: 2rem;
            border-radius: 10px;
        }
        .contact form {
            display: grid;
            gap: 1rem;
        }
        .contact input, .contact textarea {
            padding: 1rem;
            border: 1px solid #ccc;
            border-radius: 5px;
            width: 100%;
        }
        .contact button {
            background: #1abc9c;
            color: white;
            border: none;
            padding: 1rem;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background: #2c3e50;
            color: white;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Johnny Mitchell</h1>
        <p>Professional Voice Actor | Bringing Stories to Life</p>
        <nav>
            <a href="#demos">Demos</a>
            <a href="#about">About Me</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="container">
        <section id="demos" class="demos">
            <h2>Demos</h2>
            <p>Listen to some of my featured voice acting work:</p>
            <h3>COMMERCIAL DEMO WITH BG MUSIC 2.1</h3>
            <audio controls>
                <source src="COMMERCIAL DEMO WITH BG MUSIC 2.1.mp3" type="audio/mpeg">
                
            </audio>
            <h3>COMMERCIAL DEMO WITHOUT BG MUSIC</h3>
            <audio controls>
                <source src="COMMERCIAL DEMO WITHOUT BG MUSIC.mp3" type="audio/mpeg">
                
            </audio>
        </section>

        <section id="about" class="about">
            <h2>About Me</h2>
            <p>Hi, I'm Johnny Mitchell, a passionate voice actor with over a decade of experience bringing characters and stories to life. With a versatile range and a commitment to excellence, I specialize in delivering high-quality voiceovers for commercials, animations, audiobooks, and more.</p>
        </section>

        <section id="contact" class="contact">
            <h2>Contact</h2>
            <p>Have a project in mind? Let's work together! Fill out the form below to get in touch:</p>
            <form>
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Johnny Mitchell | All Rights Reserved</p>
    </footer>
</body>
</html>
