# BSC Research Plan and Thesis - BSC PhD Training Programme

## Introduction
This repository contains a LaTeX template to help you start writing your first year research plan at the Barcelona Supercomputing Center (BSC).  Additionally, you will find a second LaTeX template that you can use to build your own PhD thesis.

Both documents are inspired from the OxThesis template, which has been extensively used to write PhD thesis at the University of Oxford.  The following links provide more information about the template and the original source code:
  - https://www.oxfordechoes.com/oxford-thesis-template
  - https://github.com/mcmanigle/OxThesis

## Overleaf template
If you are new to LaTeX, you may find it more convenient to use Overleaf and work on your research plan from a web browser.  The following link contains the BSC template:
  - https://www.overleaf.com/latex/templates/bscs-research-plan/csttkgzwnvkz

## Other alternatives: Google Docs
If you and/or your supervisors cannot resist the temptation of using Microsoft Word or similar programs, then have a look at my Google Docs template:
  - https://docs.google.com/document/d/1n9lCjw-BdHzLq_CtvBy8SNvafe9gOHZOafOTZ5rQBXA/edit?usp=sharing

## LaTeX instructions
First of all, make sure that the following commands: `latex`, `latexmk`, `biber`, and `make`, are currently available on your machine; otherwise, install all the corresponding packages.  Secondly, there is a simple Makefile that automates the entire process of building your research plan from scratch.

To build your research plan execute the following command:

`make plan`

To build your PhD thesis execute the command:

`make thesis`

After compilation, you will have generated the corresponding PDFs.  In order to delete all temporary files and clean your working directory, execute either:

`make clean`

## Citation
If you want to cite this repository published at BSC GitLab:
> Pedro J. Martinez-Ferrer, "BSC Research Plan and Thesis - BSC PhD Training Programme," version v1.1, Sep. 18, 2023, URL:https://gitlab.bsc.es/pmartin1/research-plan

For convenience, the corresponding BibTeX entry is provided below:
```latex
@SOFTWARE{martinezFerrer2023,
  title = {{BSC} Research Plan and Thesis - {BSC PhD} Training Programme,
  author = {Pedro J. Martinez-Ferrer},
  year = {2024},
  date = {2024-09-27},
  version = {v1.2},
  url = {https://gitlab.bsc.es/pmartin1/research-plan}
}
```

## Acknowledgements
This work has been developed with the support of Ministerio de Ciencia e Innovación and Agencia Estatal de Investigación (MCIN/AEI/10.13039/501100011033) as well as the European Social Fund (ESF/10.13039/501100004895) under the Ramón y Cajal Fellowship Programme [grant number RYC2019-027592-I].

![](/logos/acks.png)

## Copyright
Originally by Keith A. Gillow (gillow@maths.ox.ac.uk), 1997
Modified by Sam Evans (sam@samuelevansresearch.org), 2007
Modified by John McManigle (john@oxfordechoes.com), 2015
Modified by Pedro J. Martinez-Ferrer (pedro.martinez.ferrer@upc.edu), 2022-2024

This version Copyright (C) 2022-2024 Pedro J. Martinez-Ferrer

Broad permissions are granted to use, modify, and distribute this software as specified in the MIT License included in this distribution's LICENSE file.

## Contact information
Dr. Pedro J. Martinez-Ferrer \
Departament d'Arquitectura de Computadors (DAC) \
Universitat Politècnica de Catalunya - BarcelonaTech (UPC) \
Campus Nord, Edif. D6, C. Jordi Girona 1-3, 08034 Barcelona, Spain \
pedro.martinez.ferrer@upc.edu

Barcelona Supercomputing Center (BSC) \
Pl. Eusebi Güell 1-3, 08034 Barcelona, Spain \
pedro.martinez.ferrer@bsc.es
