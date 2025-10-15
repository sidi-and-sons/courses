# Community College Courses

A basic static web site for community college courses, published using GitHub Pages.

## Features

- **Markdown Support**: Pages written in Markdown (e.g., `index.md`, `about.md`)
- **HTML Support**: Raw HTML pages with custom styling (e.g., `courses/business-101.html`)
- **Jekyll Integration**: Uses Jekyll theme for consistent styling
- **GitHub Pages Ready**: Configured with `_config.yml` for automatic deployment

## Course Catalog

Currently includes:
- **Business 101**: Introduction to Business

## Structure

```
├── _config.yml              # Jekyll configuration
├── index.md                 # Home page (Markdown)
├── about.md                 # About page (Markdown)
└── courses/
    └── business-101.html    # Business 101 course page (HTML)
```

## Viewing the Site

Once published via GitHub Pages, the site will be available at:
`https://[username].github.io/courses/`

## Adding New Courses

To add a new course:
1. Create a new HTML or Markdown file in the `courses/` directory
2. Add a link to the course in `index.md`
3. Commit and push your changes
