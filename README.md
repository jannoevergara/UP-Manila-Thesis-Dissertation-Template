# UP Manila Thesis Dissertation Template

This quarto template is custom formatted referencing UP Manila Manual of Format and Style: `https://sites.google.com/up.edu.ph/nttchplibrary/research-tools/upm-manual-of-format-style-for-td`

## Installing the extension

You will need to do this to get all the template files. Start in a diretory where you will create the folder that will contain your thesis files. Run this from a terminal in that folder.

```bash
quarto use template jannoevergara/UP-Manila-Thesis-Dissertation-Template
```

It will ask for an empty directory name where to put the files, give it a new directory name. Once ok, go inside the new directory and render the PDF files for your thesis.

This template also includes a research timeline where a Gantt chart is produced.

```bash
quarto render
quarto render Chapters/Workplan.qmd
```
## Working on the template
### Customization

You will need to customize the following files to change initial configuration and content:

* `MasterDoctoralThesis.cls` in the `_extensions/quarto-thesis` - determines the look and LaTeX environments available
* `before-body.tex` files in the `_extensions/quarto-thesis/partials` - includes the thesis title page
* `_quarto.yml` - modify for configuration

## Adding content
* Add or modify chapters and chapter content in the `Chapters` folder
* If new chapter, add the chapter in the `_quarto.yml` file

## Let's connect!
This is my [LinkedIn](linkedin.com/in/jannovergara)

## Warning
`Chapter3.qmd` and `Workplan.qmd` have R codes.