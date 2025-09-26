<p align="left">

<img src="docs/mir_logo.png" alt="MIR Logo" width="240"/>

</p>

# M:IR/NCRMP Benthic Analysis

## Introduction

Welcome to the **Mission Iconic Reef (M:IR) and National Coral Reef Monitoring Program** benthic analysis project.

This site is published at: <https://nkrampitz.github.io/MIR-Krampitz>

The purpose of this repository is to provide the data, analyses, and figures used in the above report. Others can adapt the code to produce their own format, or extract additional information from the analyses.

------------------------------------------------------------------------

## Data 

The data that feed this site include:

-   **Coral demographic measurements** (e.g. size, species, percent mortality, bleaching prevalence)\
-   **Benthic community assesment** and cover metrics\
-   **Sampling metadata** (site, date, coordinates)

collected by the NCRMP, M:IR, and DRM team in 2022 and 2024 in the Florida Keys.

You'll find both raw and processed datasets in the `data/` folder.\
When the `index.qmd` file is rendered it will reference these data files to generate tables and figures. It will also call several scripts in the `R Scripts/` folder to summarize and analyze the raw data.

------------------------------------------------------------------------

## Documents

The folder labeled "docs" contains "Index.qmd", a quarto document, which is used to generate both the HTML and the PDF outputs. In this folder, you will also find the bibliography (References.bib) and the html and pdf outputs of the quarto document.

------------------------------------------------------------------------

## Editing `index.qmd`

The report is controlled by `index.qmd`. Here's how to work with it:

-   Modify the YAML sections to update narrative or headings.
-   Change or add code blocks (R, Python) to adjust analyses, visualizations, or data pipelines.
-   Add new sections by following Quarto syntax and layout (see [Quarto Authoring Guide](https://quarto.org/docs/authoring/)).
-   After making edits to the .qmd, be sure to render the PDF before rendering the HTML so that the PDF button on the HTML page contains any updates made to the file.

------------------------------------------------------------------------

## Legal Disclaimer
This repository is a software product and is not official communication of the National Oceanic and Atmospheric Administration (NOAA), or the United States Department of Commerce (DOC). All NOAA GitHub project code is provided on an 'as is' basis and the user assumes responsibility for its use. Any claims against the DOC or DOC bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation, or favoring by the DOC. The DOC seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by the DOC or the United States Government.

------------------------------------------------------------------------

## License
Software code created by U.S. Government employees is not subject to copyright in the United States (17 U.S.C. §105). The United States/Department of Commerce reserve all rights to seek and obtain copyright protection in countries other than the United States for Software authored in its entirety by the Department of Commerce. To this end, the Department of Commerce hereby grants to Recipient a royalty-free, nonexclusive license to use, copy, and create derivative works of the Software outside of the United States.

------------------------------------------------------------------------

## Acknowledgments

-   Thanks to [Julia Mateski](https://github.com/juliamateski) and [Nicole Krampitz](https://github.com/nkrampitz) for their contributions to this respository.
