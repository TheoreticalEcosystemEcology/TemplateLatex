## Template Beamer

Beamer template for the Bayesian Summer School + a Rmarkdown integration.
Based on https://github.com/SteveViss/Rimouski.


To use the dark version, uncomment le line below in `SummerSchoolEx.tex` or
in the `header.tex` file if you use the Rmarkdown integration. 

```
% \usecolortheme{BBSDark}
```


## Compile

For the beamer latex, do:

```
pdflatex SummerSchoolEx.tex
```

To use the Rmarkdown integration, use (or click in the right place with Rstudio):

```
Rscript --no-init-file  -e 'rmarkdown::render("DemoRmarkdown.Rmd", "all")'
```



## Todo

- [X] Rmarkdown integration
