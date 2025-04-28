# MRO's auto-deploying webpage

Based on based on the [al-folio](https://github.com/alshedivat/al-folio) theme (click for original README).

#### Light/Dark Mode

This template has a built-in light/dark mode. It detects the user preferred color scheme and automatically switches to it. You can also manually switch between light and dark mode by clicking on the sun/moon icon in the top right corner of the page.

## Editing

Pages are generated from the [Markdown](https://www.markdownguide.org/basic-syntax/) files in the `_pages` directory. It's easiest to copy an existing page to create a new page. Site deploys automatically when you push changes. Note that each deployment runs the following code checks:

- [Prettier](https://prettier.io/) - check if the formatting of the code follows the style guide
- [lychee](https://lychee.cli.rs/) - check for broken links

Errors from prettier are fixed by running 'prettier [file] --write' and pushing the new file (easiest to do on Analysis after installing the [Shopify Liquid Prettier Plugin](https://www.npmjs.com/package/@shopify/prettier-plugin-liquid).

**al-folio** supports fast math typesetting through [MathJax](https://www.mathjax.org/) and code syntax highlighting using [GitHub style](https://github.com/jwarby/jekyll-pygments-themes). Also supports [chartjs charts](https://www.chartjs.org/), [mermaid diagrams](https://mermaid-js.github.io/mermaid/#/), and [TikZ figures](https://tikzjax.com/).

Photo formatting is made simple using [Bootstrap's grid system](https://getbootstrap.com/docs/4.4/layout/grid/). Easily create beautiful grids within your blog posts and project pages, also with support for [video](https://alshedivat.github.io/al-folio/blog/2023/videos/) and [audio](https://alshedivat.github.io/al-folio/blog/2023/audios/) embeds:

## Customizing

For customization details please refer to [CUSTOMIZE.md](CUSTOMIZE.md).

## License

The theme is available as open source under the terms of the [MIT License](https://github.com/alshedivat/al-folio/blob/main/LICENSE).
