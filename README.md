# oskyhn.github.io

Personal website built with Hugo. Minimalist design inspired by Bauhaus and Japanese aesthetics.

## Quick Start

### Prerequisites

- [Hugo](https://gohugo.io/installation/) (extended version recommended)

### Local Development

```bash
# Clone the repository
git clone https://github.com/oskyhn/oskyhn.github.io.git
cd oskyhn.github.io

# Start development server
hugo server -D

# Open http://localhost:1313
```

### Build

```bash
hugo --minify
```

Output will be in the `public/` directory.

## Adding Content

### New Blog Post

```bash
hugo new blog/my-post-title.md
```

### New Portfolio Item

```bash
hugo new portfolio/project-name.md
```

### New News Item

Create `content/news/news-title.md` with the appropriate front matter.

## Deployment

### GitHub Pages

1. Build the site: `hugo --minify`
2. Push the `public/` folder to the `gh-pages` branch

Or use GitHub Actions for automatic deployment.

## Project Structure

See `CLAUDE.md` for detailed documentation on the project structure and conventions.

## License

Content © Osman Kaan Yıldırım. Code available under MIT License.
