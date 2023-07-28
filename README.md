# Minimal Example of Tutorial in Quarto with R

[`index.qmd`](index.qmd) illustrates all the **required** metadata used by [`andrew`](https://github.com/GESIS-Methods-Hub/andrew).

This repository uses [install.R](install.R) as [configuration file](https://mybinder.readthedocs.io/en/latest/using/config_files.html).

## Metadata

| Markdown YAML front matter key | Required | Note |
| --- | --- | --- |
| title | ‼️ | |
| subtitle | | |
| author | ‼️ | |
| image | | Preferable as 900×600 pixels. |
| image-alt | | |

## Supported Features

| Feature | [`andrew`](https://github.com/GESIS-Methods-Hub/andrew) | Notes |
| --- | --- | --- |
| [Pandoc’s Markdown](https://pandoc.org/MANUAL.html#pandocs-markdown) | 👍 | |
| Images | 👍 | As part of Pandoc’s Markdown |
| Tables | 👍 | As part of Pandoc’s Markdown |
| Citations and Bibliographies | 👍 | As part of Pandoc’s Markdown |
| Footnotes | 👍 | As part of Pandoc’s Markdown |
| Math | 👍 | Powered by [MathJax](https://www.mathjax.org/) as part of Pandoc’s Markdown |
| Callout Blocks | 😥 | See https://github.com/GESIS-Methods-Hub/andrew/issues/149 |
| Cross References | 👍 | |
| Computation of [Inline Code](https://rmarkdown.rstudio.com/lesson-4.html) | 👍 | |
| Computation of [Code Chunks](https://rmarkdown.rstudio.com/lesson-3.html) | 👍 | |
| [Code Annotation](https://quarto.org/docs/authoring/code-annotation.html) | 👍 | Requires Quarto >= 1.3 |
| [Title Blocks](https://quarto.org/docs/authoring/title-blocks.html) | 👍 | Generated by Quarto based on YAML header |
| How to cite in the appendix | 👍 | Generated by Quarto based on YAML header |

## Binder

The link to Binder will launch [RStudio IDE](https://posit.co/products/open-source/rstudio-server/).
