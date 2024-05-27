
## Description:

Application of the wonderful [arxiv-style](https://github.com/kourgeorge/arxiv-style) template to the introspector

See **template.tex** 

## Project files:
1. **arxiv.sty** - the style file.
2. **template.tex** - a sample template that uses the **arxiv style**.
3. **references.bib** - the bibliography source file for template.tex.


Below are the commands that should be run in the project folder:
1. Run `$ latex template`
2. Run `$ bibtex template`
3. A `template.bbl` file will be generated (make sure it is there)
4. Copy the `template.bbl` file content to `template.tex` into the `\begin{thebibliography}` command.
5. Comment out the `\bibliography{references}` command in `template.tex`.
6. You ready to submit to arXiv.org.

