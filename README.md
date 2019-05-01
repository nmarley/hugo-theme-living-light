# Living Light

A Hugo theme

## Installation
From your hugo site, run:
```
git submodule add https://github.com/nmarley/hugo-theme-living-light.git themes/living-light
```

### Writing Posts
Posts that should show up in the home page must be inside `contents/posts`. Or you can change this behavior by tweaking `themes/basics/layouts/_default/list.html`.

You should also add an about page at `contents/about.md`.

Your directory should look something like this:
```
├── archetypes
│   └── default.md
├── config.toml
├── content
│   ├── about.md
│   └── posts
│       ├── my-first-post.md
│       └── my-second-post.md
├── data
├── layouts
├── static
│   └── images
└── themes
    └── basics
```

## License

[ISC](LICENSE) &copy; Nathan Marley
