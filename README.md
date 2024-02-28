# Checkpoint-HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Checkpoint</title>
</head>
<body>
    <h1>CHECKPOINT HTML</h1>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
        }

        nav {
            background-color: #444;
            padding: 1em;
            text-align: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }

        section {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
            position: absolute;
            bottom: 0;
            width: 100%;
        }

<body>

    <header>
        <h1>EL HADJI MAMADOU FALL </h1>
        <p>Web Developer</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#work">Work</a>
        <a href="#resume">Resume</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>Welcome to My Portfolio</h2>
        <p>I am a student at Gomycode, I have been following a Full stack training for 3 months to become a developer. Careers related to IT have always fascinated me. Here is my first web page creation..</p></section>

    <section id="about">
        <h2>About Me</h2>
        <p>I am a financial at heart, I have a good command of the field, professional in this sector for almost more than 12 years.</p>
    </section>

    <section id="work">
        <h2>My Work</h2>
        <p>Display your work with local links or images here.</p>
        <ul>
            <li><a href=work1.html">https://www.bing.com/videos/riverview/relatedvideo?&q=finance&&mid=0D74BEA40CA913D9381C0D74BEA40CA913D9381C&&FORM=VRDGAR</a></li>
            <iframe width="500" height="320" src="https://www.youtube.com/embed/lcZDWo6hiuI"> </iframe>>
            
            <!-- Add more projects as needed -->
        </ul>
    </section>

    <section id="resume">
        <h2>My Resume</h2>
        <p>Include your resume details and experience here.</p>
        <!-- Add a table or list for resume details -->
    </section>
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Use the form below to get in touch.</p>
        <form action="submit_form.php" method="post">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>
            <br>
            <label for="email">E-mail</label>
            <input type="email" id="email" name="email" required>
            <br>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <br>
            <input type="submit" value="Submit">
        </form>
    </section>

    <footer>
        <p>&copy; 2024 EL HADJI MAMADOU FALL | All rights reserved</p>
    </footer>

</body>

</html>     
