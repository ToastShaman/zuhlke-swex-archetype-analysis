# SWEX Curriculum Survey Analysis

## Project Description
This project analyses survey data from the SWEX Curriculum for engineering archetypes. The analysis is performed using Python and Jupyter Notebooks.

## Getting Started
To get started with the project, follow these steps:

1. Run the docker container using [just](https://github.com/casey/just):
    ```sh
    just run
    ```

    In case you do not have `just` installed:

    ```sh
    docker run -p 8888:8888 -v "${PWD}":/home/jovyan/work quay.io/jupyter/scipy-notebook:2025-02-12
    ```

2. Open your browser: `http://localhost:8888/lab?token=<TOKEN>`. The token can be found in the output of the docker container.

## Usage
Run the Jupyter Notebook to perform the analysis. The notebook contains detailed instructions and explanations for each step of the analysis.
You will need the raw survey results.

| Title                                           | Date       | Link                                                                                                                    |
|-------------------------------------------------|------------|-------------------------------------------------------------------------------------------------------------------------|
| Core Software Engineer Archetype Survey Results | 2025-03-06 | [Download](https://zuhlke-my.sharepoint.com/:x:/p/kevin_denver/EVtF82H9xgNBre987nRDntwBhs4jyfLRl_zg0NY_VUBEiw?e=hW1W3h) |
