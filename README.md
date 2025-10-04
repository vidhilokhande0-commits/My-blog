<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Tech Blog</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fafafa;
      color: #333;
      line-height: 1.6;
    }
    header, footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 1rem;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .post {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      display: flex;
      flex-direction: column;
    }
    .post h2 {
      margin: 0 0 10px;
      font-size: 1.3rem;
    }
    .post-meta {
      font-size: 0.85rem;
      color: #555;
      font-style: italic;
      margin-bottom: 10px;
    }
    .post p { flex-grow: 1; font-size: 0.95rem; }
    .read-more { text-align: right; margin-top: 10px; }
    .read-more a { color: #007BFF; text-decoration: none; font-size: 0.9rem; }
  </style>
</head>
<body>

  <header>
    <h1>My Tech Blog</h1>
  </header>

  <div class="container">
    <div class="post">
      <h2>Introduction to HTML</h2>
      <p class="post-meta">September 21, 2025 · Maaz</p>
      <p>HTML is the standard markup language for creating Web pages. It stands for Hyper Text Markup Language.</p>
      <div class="read-more"><a href="#">Read More</a></div>
    </div>

    <div class="post">
      <h2>Understanding CSS</h2>
      <p class="post-meta">September 20, 2025 · Maaz</p>
      <p>CSS describes how HTML elements are to be displayed on screen, paper, or other media. It saves a lot of work.</p>
      <div class="read-more"><a href="#">Read More</a></div>
    </div>

    <div class="post">
      <h2>JavaScript Basics</h2>
      <p class="post-meta">September 19, 2025 · Maaz</p>
      <p>JavaScript is the programming language of the Web. It can update and change both HTML and CSS.</p>
      <div class="read-more"><a href="#">Read More</a></div>
    </div>

    <div class="post">
      <h2>Responsive Design</h2>
      <p class="post-meta">September 18, 2025 · Maaz</p>
      <p>Responsive design makes your site look good on all devices using flexible layouts and media queries.</p>
      <div class="read-more"><a href="#">Read More</a></div>
    </div>

    <div class="post">
      <h2>Introduction to Git</h2>
      <p class="post-meta">September 17, 2025 · Maaz</p>
      <p>Git is a free and open-source distributed version control system designed to handle projects of any size.</p>
      <div class="read-more"><a href="#">Read More</a></div>
    </div>

    <div class="post">
      <h2>Basics of Python</h2>
      <p class="post-meta">September 16, 2025 · Maaz</p>
      <p>Python is an interpreted, high-level programming language. Its simple syntax makes it beginner-friendly.</p>
      <div class="read-more"><a href="#">Read More</a></div>
    </div>
  </div>

  <footer>
    <p>© 2025 My Tech Blog · All rights reserved.</p>
  </footer>

</body>
</html>