# Project template

Project template for setting up a directory and file structure for a new research project.
The intended contents of each directory is explained in separate README.md files.

## Overview

```
project
|- doc/                documentation for the study
|
|- data/               raw and primary data, essentially all input files, never edit!
|  |- raw_external/
|  |- raw_internal/
|  |- meta/
|
|- code/               all code needed to go from input files to final results
|- notebooks/
|
|- intermediate/       output files from different analysis steps, can be deleted
|- scratch/            temporary files that can be safely deleted or lost
|- logs/               logs from the different analysis steps
|
|- results/            output from workflows and analyses
|  |- figures/
|  |- tables/
|  |- reports/
|
|- .gitattributes      specify the files and paths attributes that should be used by git
|- .gitignore          sets which parts of the repository that should be git tracked
|- config.yml          configuration of the project workflow
|- README.md           README file in markdown
```
