# robotics
A jupyter book draft about robotics and factor graphs

Book is live at https://roboticsbook.org

Organization: 
- see [jupyter-book doc](https://jupyterbook.org/guide/01-5_tour.html)
- book content is in content subdirectory as markdown or ipython notebooks
- organized by *part*: 01...07
- ipython notebooks can have markdown and code
- the table of contents decides what is included and is in _data/toc.yml

To create a new section:
- create a markdown or ipython notebook
- add entry to toc.yml

Converting from overleaf lyx/latex
- convert to latex
- read [pandoc docs](https://pandoc.org/getting-started.html)
- `pandoc --wrap=none -f latex -t markdown file.tex > file.md`

To preview on a local machine:
- `pip install jupyter-book`
- `cd robotics`
- `jupyter-book build . `
- `make serve`

