# My Personal Page & Blog

A minimalistic, clean, and responsive personal portfolio and blog template built with pure HTML, CSS, and JavaScript. Perfect for hosting on GitHub Pages.

## Features

- 📱 Fully responsive design (mobile, tablet, desktop)
- ⚡ Fast static site (no database required)
- 🎨 Clean and minimalist aesthetic
- 🔗 Easy navigation between home and blog sections
- 📝 Simple blog post structure
- 🔒 No dependencies - just HTML and CSS
- 🚀 Free hosting on GitHub Pages

## Project Structure

```
joaofix.github.io/
├── index.html          # Home page with intro and social links
├── styles.css          # Main stylesheet (responsive)
├── README.md           # This file
└── blog/
    ├── index.html      # Blog listing page
    ├── getting-started-with-web-development.html
    ├── best-practices-for-clean-code.html
    └── why-static-sites-are-great.html
```

## Customization Guide

### 1. Update Your Information (index.html)

Edit the home page to include your actual information:

```html
<!-- Change the title -->
<title>Your Name - Developer & Writer</title>

<!-- Update the hero section -->
<h1>Hello, I'm Your Name</h1>
<p class="subtitle">Your professional tagline goes here</p>

<!-- Update your social links -->
<a href="https://github.com/your-username" target="_blank">GitHub</a>
<a href="https://twitter.com/your-handle" target="_blank">Twitter</a>
<a href="https://linkedin.com/in/your-profile" target="_blank">LinkedIn</a>
<a href="mailto:your-email@example.com">Email</a>
```

### 2. Write Blog Posts

Create new HTML files in the `/blog/` folder following the same structure as the sample posts. Remember to:

1. Create a new `.html` file in the `blog/` folder
2. Use the same HTML structure as the sample posts
3. Update the title, date, and content
4. Add a link to it in `blog/index.html`

Example blog post structure:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Post Title - Blog</title>
    <link rel="stylesheet" href="../styles.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <!-- Same as index.html -->
    </nav>

    <main class="container">
        <a href="/blog/" class="back-link">← Back to Blog</a>
        <article class="blog-post-content">
            <header class="post-header">
                <h1>Your Post Title</h1>
                <div class="post-info">
                    <span>Published on Month Day, Year</span> • <span>Reading time: X min</span>
                </div>
            </header>

            <div class="post-body">
                <!-- Your content goes here -->
            </div>
        </article>
    </main>

    <footer class="footer">
        <p>&copy; 2026 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
```

### 3. Update Navigation (Optional)

All pages include a navigation bar. If you want to add more pages, update the `<nav>` section in each file.

### 4. Customize Colors and Styling

Edit `styles.css` to change colors and styling:

```css
/* Primary color is #0066cc - change all instances to your preferred color */
a {
    color: #0066cc;  /* Change this */
}

.btn-primary {
    background-color: #0066cc;  /* Change this */
}
```

## Deployment

### Option 1: GitHub Pages (Recommended)

1. Push your code to the `main` branch of your `username.github.io` repository
2. Your site will be live at `https://username.github.io` within minutes

### Option 2: Other Hosts

You can also host this site on:
- Netlify (connect your GitHub repo, it auto-deploys)
- Vercel (similar to Netlify)
- Any web host with FTP/SFTP access

## Browser Support

This template works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Tips for Creating Content

### Home Page
- Keep your bio concise and engaging
- Highlight your main skills or interests
- Make social links easy to find

### Blog Posts
- Start with a clear introduction
- Break content into digestible sections with headers
- Use code blocks for technical content
- Keep paragraphs short for readability
- Include a "back to blog" link at the top

## Markdown Alternative

If you prefer using Markdown, consider these static site generators:
- **Jekyll** - Integrated with GitHub Pages, supports Markdown
- **Hugo** - Fast and straightforward
- **11ty** - Flexible and modern

However, the HTML approach used here requires no build step and works perfectly fine for blogs.

## License

This template is free to use and modify. Feel free to customize it for your needs.

## Questions?

Check the sample blog posts to see how to structure your content. The three included posts demonstrate different content types and formatting options.
