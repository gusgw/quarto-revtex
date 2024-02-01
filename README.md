# REVTeX

> This repository is generated from the [Github Repository Template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).

This is a Quarto template that assists you in creating a manuscript for use with revtex.

## Creating a New Article

You can use this as a template to create an article for an AFT journal. To do this, use the following command:

```bash
quarto use template vtraag/quarto-revtex
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto add vtraag/quarto-revtex
```

## Usage

To use the format, you can use the format names `revtex-pdf`. For example:

```bash
quarto render article.qmd --to revtex-pdf
```

or in your document yaml

```yaml
format:
  pdf: default
  revtex-pdf:
    keep-tex: true    
```

You can view a preview of the rendered template at < ... >.

## Format Options

You can specify the REVTeX class options using `classoption`.
