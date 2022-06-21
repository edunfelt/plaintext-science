# Emilia's Markdown Templates

## About
These are my boilerplates for authoring scientific (mainly mathematical) texts using Markdown and Pandoc.

## Requirements
- [Pandoc](https://pandoc.org/)
- [LaTeX](https://www.latex-project.org/)
- [pandoc-xnos](https://github.com/tomduck/pandoc-xnos)
- [Make](https://www.gnu.org/software/make/)

## Building
### Structure
Each toplevel subdirectory contains a template and relevant files.
A template directory contains the following:

- `Makefile`: you probably don't need to change this
- `deafults.yaml`: default pandoc settings, use this to add new sections and subsections
- `meta.yaml`: file metadata and basic layout settings
- `preamble.tex`: LaTeX layout settings
- `assets/`: contains the CSL
- `build/`: output directory
- `content/`: contains raw `.md`-files, images, and bibliography

### Instructions
Enter the directory of the desired template, edit the relevant files (see above), and run `make pdf`.

## Templates
This repo is still a work in progress while I'm migrating my scattered LaTeX templates of many years to this new format.
For now there are the following templates:

- `report`: for longer reports with sections and subsections
- `assignment`: for homework assignments, sections are problems, subsections are solutions

## Resources
The following resources have been useful in the development of this collection:

- [The Pandoc manual](https://pandoc.org/MANUAL.html#synopsis)
- [davecap/markdown-latex-boilerplate](https://github.com/davecap/markdown-latex-boilerplate)
- [jaantollander/Markdown-Templates](https://github.com/jaantollander/Markdown-Templates)
- [CSL](https://editor.citationstyles.org/about/)

