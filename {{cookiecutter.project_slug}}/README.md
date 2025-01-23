# {{cookiecutter.project_name}}

Version {{cookiecutter.version}}

{{cookiecutter.project_short_description}}


## Project organization

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

```


## License

This project is licensed under the terms of the [MIT License](/LICENSE.md)

## Citation

Please [cite this project as described here](/CITATION.md).
