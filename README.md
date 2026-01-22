# Mind of Max

My personal blog for all things I'm interested in. 

Read my lastest posts here👇

https://maxsikorski.github.io/mind-of-max-journal-blog/

<br>
<br>
<br>
<br>
Will be posting to Nostr first; stay tuned for updates
<br>
<br>
<br>
<br>
<br>
A minimal, premium personal blog built with **Serverless** web tech.

This is a **Single Page Application (SPA)** that runs directly on GitHub Pages. It uses a registry file (`posts.json`) to manage content and fetches Markdown files dynamically.

## 🚀 Features

- **Zero Build Step**: Just HTML, CSS, and JS.
- **Hash Routing**: Clean URLs (e.g., `/#article/future-of-robotics`).
- **Dark Mode**: Respects system preferences and persists user selection.
- **Instant Search**: Filter by title and tags in real-time.
- **Offline Capable**: Includes embedded content fallback for local `file://` testing.

## ✍️ How to Add a New Post

1.  **Create the Content**
    Add a new `.md` file to the `posts/` directory.
    *Example:* `posts/my-new-post.md`

2.  **Register the Post**
    Add an entry to `posts.json` at the top of the list:
    ```json
    {
      "title": "My New Post Title",
      "date": "Jan 22, 2026",
      "filename": "my-new-post.md",
      "tags": ["Life", "Tech"]
    }
    ```

3.  **Push to GitHub**
    Commit and push your changes. The site updates automatically.

## 🛠️ Local Development

Because this uses `fetch()`, most browsers block local file access (`CORS` errors).

**To preview locally:**
Simply open `index.html` in your browser.
*Note: The site has a special "Offline Mode" that detects if you are running locally and serves embedded fallback content content so you can still preview the UI.*

## 📚 Tech Stack

- **HTML5** & **Semantic CSS**
- **Vanilla JavaScript** (ES6+)
- **Marked.js** (Markdown parsing)
- **Inter Font** (Typography)
