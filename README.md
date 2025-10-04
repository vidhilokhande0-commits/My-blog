<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Nature Blog</title>
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
    <h1>My Nature Blog</h1>
  </header>

  <div class="container">
    <div class="post">
      <h2>Morning Dew & Microclimates </h2>
      <p class="post-meta">October 6, 2025 · vidhi</p>
      <p>When the world wakes slowly, dew gathers on leaves and spiderwebs, turning tiny surfaces into shimmering mirrors. Those small droplets create microclimates that help seeds germinate and insects stay hydrated — a delicate morning ritual that sustains life at the smallest scale.</p>
      <div class="read-more"><a href="#">Read More</a></div>
    </div>

    <div class="post">
      <h2>Migratory Birds: Nature’s Travelers</h2>
      <p class="post-meta">October 6, 2025 · vidhi</p>
      <p>Every year, millions of birds navigate continents using landmarks, stars, and magnetic cues to find breeding and wintering grounds. Watching a small flock pass overhead reminds us that ecosystems are connected across thousands of kilometers.</p>
      <div class="read-more"><a href="#">Read More</a></div>
    </div>

    <div class="post">
      <h2>Native Wildflowers & Pollinators</h2>
      <p class="post-meta">October 6, 2025 · vidhi</p>
      <p>Native wildflowers have evolved hand-in-hand with local bees, butterflies, and beetles, offering the correct nectar and bloom timing for pollination. Planting them supports biodiversity and keeps fragile food webs intact in both wild and urban spaces.</p>
      <div class="read-more"><a href="#">Read More</a></div>
    </div>

    <div class="post">
      <h2>Urban Green Spaces</h2>
      <p class="post-meta">October 6, 2025 · vidhi</p>
      <p>Pocket parks, rooftop gardens, and tree-lined streets transform concrete into cool, breathable places that improve air quality and mental health. Even small patches of green create corridors for birds and insects, stitching nature back into the city fabric.</p>
      <div class="read-more"><a href="#">Read More</a></div>
    </div>

    <div class="post">
      <h2>Fungi: Nature’s Recyclers</h2>
      <p class="post-meta">October 6, 2025 · vidhi</p>
      <p>Fungi quietly break down fallen wood and dead leaves, returning nutrients to the soil and enabling new growth to begin. Their underground networks also link trees, allowing communication and resource sharing across the forest floor.</p>
      <div class="read-more"><a href="#">Read More</a></div>
    </div>

    <div class="post">
      <h2>Night Sky & Light Pollution</h2>
      <p class="post-meta">October 6, 2025 · vidhi</p>
      <p>A truly dark night reveals a sky crowded with stars — a reminder of scale and time beyond our daily worries. Excessive artificial lighting erases this view and disrupts nocturnal animals, so small changes to outdoor lights can restore both starlight and wildlife rhythms.</p>
      <div class="read-more"><a href="#">Read More</a></div>
    </div>
  </div>

  <footer>
    <p>© 2025 My Nature Blog · All rights reserved.</p>
  </footer>

</body>
</html>