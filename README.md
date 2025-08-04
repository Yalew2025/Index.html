# Index.html
This repository about a web developed using HTML and VS code with python programming language.


<!DOCTYPE html> <!-- Step 1: Declare HTML5 document type -->
<html lang="en"> <!-- Step 2: Set language for accessibility and SEO -->
    
<head>
    <!-- Step 3: Metadata for SEO & accessibility -->
    <meta charset="UTF-8"> <!-- Character encoding -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Mobile-friendly -->
    <meta name="description" content="A beginner-friendly, accessible HTML5 webpage demonstrating semantic structure and SEO principles."> <!-- SEO meta description -->
    <meta name="author" content="Yalew Abiyu"> <!-- Optional author info -->

    <!-- Step 4: Page title (appears in browser & search results) -->
    <title>Accessible & SEO-Friendly HTML5 Page</title>
</head>

<body>
    <!-- Step 5: Header landmark for page intro -->
    <header>
        <h1>Welcome to My Accessible HTML5 Webpage</h1> <!-- Main heading for SEO -->
        <p>This page demonstrates semantic structure, accessibility, and SEO basics.</p>
    </header>

    <!-- Step 6: Navigation landmark -->
    <nav aria-label="Main Navigation"> <!-- Accessibility: descriptive label for screen readers -->
        <ul>
            <li><a href="#about" title="Learn more about this page">About</a></li>
            <li><a href="#articles" title="Read featured articles">Articles</a></li>
            <li><a href="#contact" title="Get in touch">Contact</a></li>
        </ul>
    </nav>

    <!-- Step 7: Main landmark for primary content -->
    <main>
        <!-- Section 1 -->
        <section id="about">
            <h2>About This Page</h2>
            <p>This is a simple, well-structured HTML5 document using semantic tags to improve both human and machine readability.</p>
        </section>

        <!-- Section 2 -->
        <section id="articles" aria-labelledby="articles-heading">
            <h2 id="articles-heading">Featured Articles</h2>
            
            <!-- Article 1 -->
            <article>
                <h3>Why Semantic HTML Matters</h3>
                <p>Semantic HTML improves SEO, accessibility, and code maintainability. Search engines understand your content better, and assistive technologies can navigate it easily.</p>
            </article>

            <!-- Article 2 -->
            <article>
                <h3>Accessibility Best Practices</h3>
                <p>Using HTML5 landmarks, descriptive links, and clear heading hierarchies makes the web more inclusive for everyone.</p>
            </article>
        </section>
    </main>

    <!-- Step 8: Footer landmark -->
    <footer>
        <section id="contact">
            <h2>Contact</h2>
            <address>
                Email: <a href="email to: yalew6vet21@gmail.com">yalew6vet21@gmail.com</a><br>
                Location: Addis Ababa, Ethiopia
            </address>
        </section>
        <p>&copy; 2025 Yalew Abiyu. All rights reserved.</p>
    </footer>
</body>
</html>
