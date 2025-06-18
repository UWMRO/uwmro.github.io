# MRO's auto-deploying webpage

Based on based on the al-folio theme [(click here for original README)](https://github.com/alshedivat/al-folio).

#### Light/Dark Mode

This template has a built-in light/dark mode. It detects the user preferred color scheme and automatically switches to it. You can also manually switch between light and dark mode by clicking on the sun/moon icon in the top right corner of the page.

## Editing

Pages are generated from the [Markdown](https://www.markdownguide.org/basic-syntax/) files in the `_pages` directory. It's easiest to copy an existing page to create a new page. Site deploys automatically when you push changes. 

Code syntax highlighting using [GitHub style](https://github.com/jwarby/jekyll-pygments-themes). Math typesetting supported through [MathJax](https://www.mathjax.org/), with additional support for [chartjs charts](https://www.chartjs.org/), [mermaid diagrams](https://mermaid-js.github.io/mermaid/#/), and [TikZ figures](https://tikzjax.com/).

"Photo formatting is made simple using [Bootstrap's grid system](https://getbootstrap.com/docs/4.4/layout/grid/). Easily create beautiful grids within your blog posts and project pages, also with support for [video](https://alshedivat.github.io/al-folio/blog/2023/videos/) and [audio](https://alshedivat.github.io/al-folio/blog/2023/audios/) embeds" [(See original README)](https://github.com/alshedivat/al-folio)

## Customizing

For customization details please refer to [CUSTOMIZE.md](CUSTOMIZE.md).

### Disabled Actions

`Check for broken links` disabled since it counts any internal link as an error.

`Check for broken links on site` disabled since, after clean-up, it doesn't find any serious errors but takes a long time to do so.

`Prettier code formatter` disabled since our goal is to make the markdown easy to edit. If it's desired to reanble it, errors from prettier are fixed by running 'npx prettier -w [file]' and pushing the new file (easiest to do on Analysis after installing the [Shopify Liquid Prettier Plugin](https://www.npmjs.com/package/@shopify/prettier-plugin-liquid)).


## License

The theme is available as open source under the terms of the [MIT License](https://github.com/alshedivat/al-folio/blob/main/LICENSE).
