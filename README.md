# Good Enough Project

A cookiecutter project structure based on the [Reproducible Science Cookiecutter](https://github.com/mkrapp/cookiecutter-reproducible-science) template by [Mario Krapp](https://github.com/mkrapp), and with close resemblances to the philosophy of [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science): *A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.*

The name (and most of the structure) are derived from the paper [Good Enough Practices in Scientific Computing](https://doi.org/10.1371/journal.pcbi.1005510), Wilson _et al._, PLOS Computational Biology (2017).

## Requirements

Install `cookiecutter` on the command line: `pip install cookiecutter`    

## Usage

To start a new science project:

`cookiecutter gh:RamonvanValderen/cookiecutter-simulations`

## Project Structure

The project structure distinguishes three kinds of folders:
- read-only (RO): not edited by either code or researcher
- human-writeable (HW): edited by the researcher only.
- project-generated (PG): folders generated when running the code; these folders can be deleted or emptied and will be completely reconstituted as the project is run.


```
.
├── .gitignore
├── CITATION.md
├── LICENSE.md
├── README.md
├── requirements.txt
├── 1-metadata            
│   └── 1-geometry_files            <- .stl or .step files of geometry
│   └── 2-drawings                  <- drawings with dimensions and different views of geometries
├── 2-simulations                   <- all simulation files with logical folder names
├── 3-data_analysis_methods         <- All files related to the analysis of the data, such as Python, Julia or Matlab files
├── 4-docs                          <- Documentations
│   ├── 1-datasets                  <- Any datasets used from literature or own lab data
│   └── 2-cover_letter              <- Cover letter for submission
├── 5-results
│   ├── 1-figures                   <- Figures for the manuscript or reports (PG)
│       └── 1-final_figures
│       └── 2-notebook_figures      <- Figures from notebooks (not for publishing)
│       └── 3-graphical_abstract    
│       └── 4-other                 <- For other images or movies
│   └── 2-manuscript                <- Manuscript source, e.g., LaTeX, Markdown, etc. (HW) and final PDF
│       └── 1-feedback              
│       └── 2-backups   
├── 99-tests                        <- Testing simulations, later to be deleted
└── src                             <- Source code for this project (HW)



## License

This project is licensed under the terms of the [MIT License](/LICENSE.md).
