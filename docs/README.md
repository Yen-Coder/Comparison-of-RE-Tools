# Documentation Site

This directory contains the GitHub Pages site for the Comparison of Reverse Engineering Tools project.

## Structure

```
docs/
├── index.md              # Landing page
├── _config.yml           # Jekyll configuration
├── _layouts/             # Custom layouts
│   └── default.html      # Main layout with sidebar
├── _includes/            # Reusable components
│   └── sidebar.html      # Sidebar navigation
├── assets/
│   └── css/
│       └── sidebar.css   # Sidebar styling
└── wiki/                 # Wiki pages
    ├── _Sidebar.md       # Sidebar navigation content
    ├── Home.md           # Wiki home
    └── ... (other pages)
```

## Local Development

To run the site locally:

```bash
cd docs
bundle install
bundle exec jekyll serve
```

Then visit http://localhost:4000/Comparison-of-RE-Tools/

## Live Site

https://your-username.github.io/Comparison-of-RE-Tools/

---

[↑ Back to Top](#documentation-site)