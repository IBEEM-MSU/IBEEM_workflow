# IBEEM_workflow
Information related to reproducible workflow format for IBEEM

This repository contains code and workflows for research projects within IBEEM (MSU SPG-sponsored Institute for Biodiversity, Ecology, Evolution, and Macrosystems). 

## Location of data

These data are stored in a Google Shared Drive and the MSU HPCC IBEEM research space, accessible by collaborators. IBEEM research projects will publish open access data to accompany research papers.

## Workflow

All repositories should follow R packaging guidelines, even if they will not become official R packages. For questions, contact Pat Bills. 

The workflow for this repository follows the guidelines set out by the [Environmental Data Initiative (EDI)](https://environmentaldatainitiative.org/). Briefly, this involves aligning with FAIR data practices, and employing a workflow that uses different levels for harmonization and derived data products. The overall workflow aligns with this EDI diagram: 

<img src="https://environmentaldatainitiative.files.wordpress.com/2019/04/harmonization_procedure_general.png" alt="hi" class="inline"/>

## Description of subdirectories 

- **R**: Main directory containing R scripts. Subdirectories below.
- **/L0**: Code & small text data files. 
- **/L1**: Code to create L1 data products = cleaning & editing L0 data. 
- **/L2**: Code to create derived products from L1 data (e.g., merging 2 or more L1 data products).

### docs
- documents supporting the data and analysis.

## Funding 
Funding is provided by Michigan State University Strategic Partnership Grant for IBEEM. 

## Authors of this repository

* Phoebe L. Zarnetske
* Pat Bills
