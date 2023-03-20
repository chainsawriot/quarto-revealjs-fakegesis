# Quarto reveal.js template - fakegesis

This is a repository for `Quarto` `reveal.js` template. And this is not an official product. Please use the official Powerpoint template.

But this is a demo: [https://chainsawriot.github.io/fakegesis/](https://chainsawriot.github.io/fakegesis/)

## Installation

This [Quarto](quarto.org) template can be installed/used using the following command:

```bash
quarto use template chainsawriot/quarto-revealjs-fakegesis
```

## Speedrun

For this particular example, you'll need R, `ggplot2` and `plotly`.

```bash
## Step 1: create an empty directory
mkdir slides
cd slides
## Step 2: use the template
quarto use template chainsawriot/quarto-revealjs-fakegesis --no-prompt
## Step 3: render
quarto render slides.qmd
## Step 4: there is no step 4
xdg-open slides.html
```

## Documentation

[`Quarto` documentation on `reveal.js` format.](https://quarto.org/docs/presentations/revealjs/)

## Acknowledgment

This is a fork of [quarto-revealjs-umr1283](https://github.com/umr1283/quarto-revealjs-umr1283) (CC-BY-4.0, Mickaël Canouil).
