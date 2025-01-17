
<!-- README.md is generated from README.Rmd. Please edit that file -->

# quillt <img src='man/figures/logo.png' align="right" height="139" />

## Overview

quillt is a [pkgdown](https://pkgdown.r-lib.org) template for packages
in the R Markdown ecosystem. The goal of quillt is to create a patchwork
quilt of all the packages that R Markdown users benefit from. That means
packages that help users extend R Markdown using new output formats and
templates, or that build upon existing packages to improve the quality
of life for R Markdown users. If you feel that your package fits, please
feel free to use this template for your own package.

The theme is built on top of the [paper bootswatch
theme](https://bootswatch.com/3/paper/).

## Using quillt

Make sure your `_pkgdown.yaml` contains:

``` yaml
template:
  package: quillt

development:
  mode: auto

home:
  strip_header: false
```

You can customise the “part of” in the header and the footer text.

``` yaml
template:
  package: quillt
  params:
    part_of: rmarkdown.io
    footer: ...
```

To work properly, quillt requires the css files in
`inst/pkgdown/assets/`. Because of this, you should not set
`default_assets: false` in your `_pkgdown.yaml`.

``` yaml
template:
  package: quillt
  # Do not do this!
  default_assets: false
```

## CSS files

Three CSS files play a role in styling the site:

-   `tidyverse.css` is generated from files in `scss/` written by Robby
    Shaver. Generally you should not touch these files; Robby is the
    owner. If needed you can regenerate `tidyverse.css` by running this
    code:

    ``` r
    # devtools::install_github("rstudio/sass")
    library(sass)
    sass(
      sass_file("scss/tidyverse.scss"),
      output = "inst/pkgdown/assets/tidyverse.css",
      options = sass_options(output_style = "nested")
    )
    ```

-   `pkgdown.css` comes from pkgdown.

## Lorem Ipsum

Added to make the readme long enough that I can check scrolling.

Lorem ipsum dolor sit amet, ea pri paulo facete, in mel choro volumus.
Dolore labitur cum no, vis copiosae appareat ex, vix antiopam iudicabit
consequat in. Has equidem graecis et. Ea est partem altera, ius id agam
debitis. Ex mea minim utroque, harum choro at has.

Vim rebum denique ad. Vocent dignissim ea qui, mea no vocent eruditi. At
vix soleat bonorum comprehensam, qui nibh sale epicurei te, ex ullum
dicta sit. Sed te vide nostrud. Denique delicata ut vim.

Nec no nobis scaevola, ad his commodo qualisque liberavisse. Sed porro
propriae repudiare et, enim viris definitionem mei an. Ridens deserunt
conceptam usu et. Cu has eros dicit, ex nec idque fabulas. Eum ei
sensibus mnesarchum dissentias.

Eum id essent pericula salutandi, cu mazim congue molestiae usu. No has
omnesque conclusionemque, no eos nusquam offendit expetendis. Alii
oratio ad usu. Et pri feugait recusabo salutandi, ius ad commune
salutandi. Ut graece vivendum vim, decore qualisque mediocritatem vix
cu.

Ei nullam postea interesset vix, vix eu case fugit graeco, nec ut
ponderum deserunt. Has ex amet neglegentur, eos et porro debet eirmod.
Te pri lorem persius facilisis. Eos liber mentitum nominavi id.
