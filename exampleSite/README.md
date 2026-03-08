# FixIt Theme - Example Site

This is an example site for testing the [FixIt Hugo theme](https://github.com/AIPulseStudio/hugo-theme-fixit).

## Quick Start

### Start the development server

```bash
cd exampleSite
hugo server -D --port 1315
```

Then visit http://localhost:1315/ to see the result.

## Configuration

The site uses the parent directory's theme via Hugo modules:

```toml
[module]
[[module.mounts]]
source = "../layouts"
target = "layouts"
```

## Site Structure

```
exampleSite/
├── hugo.toml          # Configuration file
├── content/
│   ├── _index.md      # Home page
│   └── posts/         # Blog posts
│       ├── welcome-to-fixit.md
│       └── test-post.md
└── README.md
```

## Menu

- Home (/)
- Posts (/posts/)
- About (/about/)

## Theme Features

FixIt theme includes:

- 🎨 Clean and modern design
- 📱 Fully responsive
- 🌙 Dark mode support
- 🚀 Fast performance
- 🔍 Search functionality
- 📝 Markdown support
- 🏷️ Tags and categories

For more information, visit the [FixIt documentation](https://fixit.lruihao.cn/).
