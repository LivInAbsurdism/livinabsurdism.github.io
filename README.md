# livinabsurdism.github.io

Personal blog and portfolio site for Liv Cella, a backend engineer passionate about technology, open source, and sustainable living.

🌐 **Live Site:** [https://livinabsurdism.github.io](https://livinabsurdism.github.io)

## About

This is a Jekyll-based static site hosted on GitHub Pages, featuring technical blog posts, project updates, and personal insights on programming, Linux systems, and various side projects.

## Tech Stack

- **Static Site Generator:** [Jekyll](https://jekyllrb.com/)
- **CSS Framework:** [Bootstrap 3.3.6](http://getbootstrap.com/)
- **Markdown Processor:** Kramdown
- **Hosting:** GitHub Pages

## Features

- ✨ Clean, minimalist design with a terminal-inspired aesthetic
- 📝 Blog posts with syntax highlighting for code
- 🏷️ Category and tag organization
- 📱 Fully responsive layout
- 🎯 Custom 404 page
- 📊 Analytics support (optional)
- 💬 Disqus comments support (optional)
- 📡 RSS feed

## Project Structure

```
.
├── _config.yml          # Site configuration
├── _includes/           # Reusable HTML components
├── _layouts/            # Page templates
├── _posts/              # Blog posts organized by year
│   └── 2017/
├── css/                 # Stylesheets and Bootstrap
├── images/              # Images and media assets
├── blog.md              # Blog listing page
├── category.md          # Category page
├── index.md             # Homepage
└── feed.xml             # RSS feed
```

## Local Development

### Prerequisites

- Ruby (2.5 or higher)
- Bundler
- Jekyll

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/livinabsurdism/livinabsurdism.github.io.git
   cd livinabsurdism.github.io
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the local server:
   ```bash
   bundle exec jekyll serve
   ```

4. Visit `http://localhost:4000` in your browser

### Creating New Posts

Posts are stored in `_posts/` organized by year. Create a new post using the naming convention:

```
_posts/YYYY/YYYY-MM-DD-title-of-post.md
```

Post front matter example:
```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS
categories:
    - blog
tags:
    - tag1
    - tag2
---
```

## Configuration

Key settings in `_config.yml`:

```yaml
title: "absurd revolt"
url: "http://livinabsurdism.github.io"
nick: "livinabsurdism"
markdown: kramdown
permalink: /:categories/:title/
```

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the main branch. No additional build steps required.

## Credits

- Theme inspired by [Clyell](https://github.com/gjuniioor/clyell) by [@gjuniioor](https://github.com/gjuniioor)
- Responsive design contributions by [@magnunleno](https://github.com/magnunleno)

## License

See [LICENSE](LICENSE) file for details.
