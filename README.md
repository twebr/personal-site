# Thijs Meeuwisse's website

This repository hosts the source code of my personal website.

## Design philosophy

I try to minimise my dependencies.

## Technologies used

- [Hugo](https://gohugo.io/)
- [Quarto](https://quarto.org)
    - See [this guide](https://quarto.org/docs/output-formats/hugo.html) for integrating Hugo with Quarto

## Commands

To run a development server, use

```sh
hugo server
```

Useful flags:

- `-D` to include content marked as draft
- `--disableFastRender` to enable full re-renders on changes

## Deployment

...

## Other useful tools

For batch manipulating the front matter of the content, I can heartily recommend [Python Frontmatter](https://python-frontmatter.readthedocs.io/en/stable/).

## Themes

I built my own theme based on the skeleton theme that is generated with `hugo new theme`.
I moved the source code from the `/themes` directory to the root directory, to flatten the directory structure.
