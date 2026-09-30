# Nannan Zhang · Academic homepage

Personal academic website for [Nannan Zhang](https://moria5161.github.io), built with Jekyll and compatible with GitHub Pages.

## Content

- `_pages/about.md`: homepage, biography, research interests, and Ramancloud news.
- `_pages/publications.md`: publications; currently “Coming soon.”
- `_pages/cv.md`: curriculum vitae.
- `_includes/education.html`: education timeline shared by the homepage and CV.
- `_includes/research-interests.html`: shared research interests.
- `_config.yml`: name, email, GitHub account, and site metadata.
- `assets/css/academic.css`: responsive academic theme.

The education timeline records the 2023–2026 master's studies in Materials Engineering at Xiamen University's College of Chemistry and Chemical Engineering, and the Ph.D. in Artificial Intelligence at its Institute of Artificial Intelligence from 2026 onward. Both are advised by [Prof. Bin Ren](https://bren.xmu.edu.cn).

## Local preview

Use a current Ruby version (3.1 or newer recommended):

```sh
bundle install
bundle exec jekyll serve
```

Open the local URL printed by Jekyll. To build only:

```sh
bundle exec jekyll build
```

## GitHub Pages

The repository remote points to `moria5161/moria5161.github.io`. Publish through the repository's configured GitHub Pages source branch. No frontend build service or Node.js installation is needed. The existing `/about/`, `/about.html`, and `/resume` redirects are retained.

The original Academic Pages template files are retained, but its demonstration posts, papers, talks, teaching, and portfolio pages are excluded from the published site.

## Design credits

The compact profile layout, purple links, green accents, and education timeline take inspiration from [Xinyu Lu's homepage](https://github.com/X1nyuLu/x1nyulu.github.io). Personal content and portrait come from Nannan Zhang's original site. The underlying Academic Pages / Minimal Mistakes template retains its original license.
