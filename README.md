
## Template Beamer

Beamer template for the Bayesian Summer School and its Rmarkdown integration.
Based on https://github.com/SteveViss/Rimouski (I guess it's based on what
Tim did).

To use the dark version, uncomment le line below in `SummerSchoolEx.tex` or
in the `header.tex` file if you use the Rmarkdown integration.


```
% \usecolortheme{BBSDark}
```



## Compile

For the beamer Latex, use `pdflatex` like so:

```
pdflatex SummerSchoolEx.tex
```

To use and `.Rmd` files instead, use the following command (or click in the right
place if you are a Rstudio user):

```
Rscript --no-init-file  -e 'rmarkdown::render("DemoRmarkdown.Rmd", "all")'
```



## Todo

- [ ] This could be a repo to store more templates (for different documents)
NB: I may not have picked up the right name.
