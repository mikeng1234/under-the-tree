# Under the Tree

A mobile-friendly collection of thoughts written under a tree at the park with the large oval.

## Browsing

Open `index.html` in any mobile browser — or enable GitHub Pages in your repo settings to get a live URL.

## Adding a thought

Add a new `<article class="thought-card">` block inside `<main id="thoughts">` in `index.html`:

```html
<article class="thought-card">
  <time datetime="YYYY-MM-DD">Month Day, Year</time>
  <h2>Title</h2>
  <p>Your thought here.</p>
  <span class="tag">tag</span>
</article>
```

## Features

- Mobile-first responsive design (max 640px content width)
- Dark mode support for outdoor reading
- Clean card-based layout
- No JavaScript dependencies — pure HTML & CSS
