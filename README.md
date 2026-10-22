# html_css_practice

Layout exercises and small projects from learning HTML and CSS.

**Live:** https://harshaannihal.github.io/html_css_practice/

## What is in here

- `Project/Day-N/` holds the daily layout exercises, one folder per layout.
- `Project/final_project1/` and `Project/final_project2/` are the two final layouts.
- `portfolio/` is an early version of the portfolio, now at [harshaannihal.github.io](https://harshaannihal.github.io/).
- `styles-conference/` is a five-page conference site.
- `hello_world/` is a hello-world page.

Everything is plain HTML and CSS. Open any `index.html` in a browser to run it. No build step.

## The index page

`index.html` at the repo root lists every page and is generated. After adding or moving an exercise, regenerate it:

```sh
python3 tools/build_index.py --title "HTML & CSS Practice" --blurb "Layout exercises and small projects from learning HTML and CSS, grouped by folder." --repo https://github.com/harshaanNihal/html_css_practice
```
