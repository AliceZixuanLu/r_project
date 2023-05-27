# codespaces_r_env
Codespace template for R languange, create R project repository by using this template. It will create the R envirionment automatically with neccessary packages. visit https://github.com/bg4xsd/codespaces_python_env for more detailed usage.

1. https://github.com/microsoft/vscode-dev-containers is moving to https://github.com/devcontainers. keep tracking https://github.com/devcontainers/images/tree/main/src and finding your images.

2. https://github.com/devcontainers/images/tree/main/src/universal, Use or extend the new Ubuntu-based default, large, and multi-language universal image which contains many popular languages/frameworks/SDKS/runtimes. It's chosen for Python Env, and can be used for R, too.

3. If you want a Python-R inter-active environment, try to use https://github.com/devcontainers/images/tree/main/src/miniconda, and install Python, R packages using conda, it's easy and simple.

4. For a simple R environment, visit https://github.com/rocker-org/devcontainer-templates/tree/main/src/r-ver, rocker-org is a repository dedicated to R. Visit it and find your images.

5. rocker-org/rocker-versioned2, at https://github.com/rocker-org/rocker-versioned2, includes rstudio, tidyverse, verse, geospatial. It seems powerful.

6. rocker/verse has already installed TeX Live and some publishing-related R packages, in addition to the packages installed in rocker/tidyverse.

7. I recommend to use rocker/tidyverse for general study purpose, which includes the tidyverse package, the devtools package, the rmarkdown package, some R Database Interface packages, the data.table package, the fst package, and the Apache Arrow R package. Check https://rocker-project.org/images/ for your images. If you like, try https://rocker-project.org/images/#the-versioned-stack for stable images. The URL can be found at https://github.com/orgs/rocker-org/packages?repo_name=rocker-versioned2.

9. Finaly， I choose r-ver：4 for my research, it seems more stably running on Github.

Result:

   It DO work and should work well, but most time, you will meet lots of problem, extrally when you use devcontainer-feature to install jupyter. You have to try several times, I guess it is not the problem of rocker-project, it would be some bugs of Cache system from Github, . Anyway, there is another choice, turn to Python env with conda, and install R by conda.
   
   Good luck.

Last update: by BG4XSD @ 2023.05.26 

