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
├── 1-bin                   <- Compiled and external code, ignored by git (PG)
│   └── external            <- Any external source code, ignored by git (RO)
├── 2-config                <- Configuration files (HW)
├── 3-simulation_input      <- All input files to run a simulation, software specific
│   └── metadata            <- All metadata regarding simulation
├── 4-simulation_output     <- All raw data generated from simulation
├── 5-data_analysis_methods <- All files related to the analysis of the data, such as Python, Julia or Matlab files
├── 6-docs                  <- Documentation notebook for users (HW)
│   ├── manuscript          <- Manuscript source, e.g., LaTeX, Markdown, etc. (HW)
│   └── reports             <- Other project reports and notebooks (e.g. Jupyter, .Rmd) (HW)
├── 7-results
│   ├── figures             <- Figures for the manuscript or reports (PG)
│   └── output              <- Other output for the manuscript or reports (PG)
└── src                     <- Source code for this project (HW)

```


## License

This project is licensed under the terms of the [MIT License](/LICENSE.md)

## Citation

Please [cite this project as described here](/CITATION.md).
