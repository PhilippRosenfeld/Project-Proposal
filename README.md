# Project Proposal

LaTeX source for our project proposal.

## Structure

```
main.tex            # entry point (title, packages, includes)
sections/*.tex      # one file per section – edit these
references.bib      # bibliography (biblatex + biber)
figures/            # images
```

## Working on it

**On Overleaf:** open the linked Overleaf project, edit, then use
*Menu → GitHub → Push/Pull* to sync with this repo.

**Locally:**

```bash
git clone <repo-url>
latexmk -pdf main.tex
```

**Workflow:** pull before you start, keep commits small, and preferably work in
separate section files to avoid merge conflicts. Use `\todo{...}` for open points.
