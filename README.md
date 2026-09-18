# Personal website

A single-page academic website. Edit the biography and research in `index.Rmd`,
the layout in `_template.html`, and the appearance in `theme.css`.

Build the GitHub Pages output in `docs/` from RStudio using **Build Website**, or
run this in an R session with `rmarkdown` and Pandoc available:

```r
rmarkdown::render_site()
```

To rebuild just the home page:

```r
rmarkdown::render_site("index.Rmd")
```

Open `docs/index.html` in a browser to preview the result. Commit the source files
and the rebuilt `docs/` output when publishing through GitHub Pages.
