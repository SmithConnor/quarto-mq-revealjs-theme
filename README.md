# Macquarie University Quarto reveal.js Presentation Template

> Template for creating a new reveal.js article format for Quarto. 
>
> See information about how-to use this repo template inside the template file.

This is a Quarto template that assists you in creating a presentation for use with Macquarie University branding. You can learn more about ...

## Creating a New Presentation

You can use this as a template to create a reveal.js presentation with a Macquarie University theme. To do this, use the following command:

```bash
quarto use template SmithConnor/quarto-mq-revealjs-theme
```

This will install the extension and create an example qmd file that you can use as a starting place for your presentation.

## Installation For Existing Document

You may also use this format with an existing Quarto project or presentation. From the quarto project or presentation directory, run the following command to install this format:

```bash
quarto install extension SmithConnor/quarto-mq-revealjs-theme
```

## Usage

To use the format, you can use the format name `mq-revealjs`. For example:

```bash
quarto render article.qmd --to mq-revealjs
```

or in your document yaml

```yaml
format:
  mq-revealjs
```

## Code Snippets

Addition code snippets have been created for use in `RStudio`.

