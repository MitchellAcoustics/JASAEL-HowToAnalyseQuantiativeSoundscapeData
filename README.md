# How To Analyse and Represent Quantitative Soundscape Data - JASA Express Letters

This repository contains the code and data for the paper "How To Analyse and Represent Quantitative Soundscape Data" published in JASA Express Letters. The paper is available at [https://doi.org/10.1121/10.0009794](https://doi.org/10.1121/10.0009794).

## Abstract
This study first examines the methods presented in ISO 12913 for analysing and representing soundscape data by applying them to a large existing database of soundscape assessments. The key issue identified is the inability of the standard methods to summarise the soundscape of locations and groups. The presented solution inherently considers the variety of responses within a group and provides an open-source visualisation tool to facilitate a nuanced approach to soundscape assessment and design. Several demonstrations of the soundscape distribution of urban spaces are presented, along with proposals for how this approach can be used and developed.

## Rendered paper

The paper rendered directly from this repository can be found in the [paper](paper) folder.

## Running the code

The code is written in Python and uses a quarto notebook. To run the code, you can use the included [devcontainer](https://containers.dev). On Github this can be done by clicking on the green "Code" button and selecting "Open with Codespaces". This will open the code in a containerised environment with all dependencies installed within your browser. 

Alternatively, you can run the code locally by opening the repo in Visual Studio Code with the Remote - Containers extension installed and selecting "Reopen in Container" from the command palette. Finally, you can run the code on your local machine by installing the quarto and the Python dependencies using `uv sync` which will install the dependencies in a virtual environment.

Once you have a code environment setup you can run the code by opening the `paper.qmd` file and running the code cells. The paper can be rendered by running `quarto render` in a terminal.
