<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Ali</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div>
            <h1>Ali Ertene</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="projects.html">Projects</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section>
        <h2>Contact Me</h2>
        <form action="https://formspree.io/f/myybjglv" method="POST">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" placeholder="Your Name" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="_replyto" placeholder="Your Email" required>

            <label for="message">Message</label>
            <textarea id="message" name="message" placeholder="Your Message" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <div>
            <p>&copy; 2024 Ramazan Demir KPI</p>
        </div>
    </footer>
</body>
</html>
