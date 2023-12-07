# Markdown Resume

This repo allows you to build & maintain your resume in a Markdown file, and then publish it into an HTML, PDF or Word file.

The inspiration for this project came from my need to look for a job. So I opened Google Docs to update my resume and just groaned.

I've been writing Markdown for over a decade, starting with the [Ulysses](https://ulysses.app/) MacOS app, and now [Obsidian](https://obsidian.md/). I try not to use non-markdown editors anymore if I can help it.

So I looked around and found this repo by [VidLuther](https://github.com/vidluther/markdown-resume).
Who was inspired by this [project by Sonya Sawtelle](https://sdsawtelle.github.io/blog/output/simple-markdown-resume-with-pandoc-and-wkhtmltopdf.html).

I've added a `package.json` to this project, so you can easily run the scripts. I've used my name to generate the files, but feel free to configure it as you please.

## Workflow

The workflow is pretty simple.

1. Edit the resume.md file.
2. Run `npm run all` to generate your HTML, PDF & Word Doc

## Pre-Requisites

Install these packages globally.

### [Pandoc](https://pandoc.org) - a universal document converter

```shell
brew install pandoc
```

### [Wkhtmltopdf](https://wkhtmltopdf.org) - to convert your Markdown to PDF

```shell
brew install wkhtmltopdf
```

### Install the Package Scripts

```shell
npm install
```

## Package Scripts

### Create All 3 Files / PDF, HTML & Word Doc

```shell
npm run all
```

### Markdown to HTML

```shell
npm run html
```

### Markdown to PDF

```
npm run pdf
```

### HTML to PDF

```
npm run html:pdf
```
