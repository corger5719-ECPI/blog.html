<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blog Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>My Learning Blog</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#blog">Blog</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <main id="home">

        <section id="blog" class="blog-container">

            <article class="blog-post fade-in">
                <h2>First Blog Post</h2>
                <p>This is some sample text for the first blog post. I am learning how to structure HTML documents.</p>
                <p>Using semantic elements makes the webpage easier to read and understand.</p>
            </article>

            <article class="blog-post fade-in">
                <h2>Second Blog Post</h2>
                <p>This is another sample blog post. I am practicing Flexbox for layout design.</p>
                <p>I will also apply media queries to make the page responsive.</p>
            </article>

        </section>

        <section id="contact" class="contact-section fade-in">
            <h2>Contact Me</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="subject">Subject:</label>
                <input type="text" id="subject" name="subject">

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <input type="submit" value="Send Message">
            </form>
        </section>

    </main>

    <footer>
        Student ID: CORGER5719 &copy; 2025
    </footer>

</body>
</html>
