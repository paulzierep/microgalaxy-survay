# microGalaxy user paper

This GitHub repository store sources (scripts, data, images) for the microGalaxy user paper stats

## Structure of the repository

Folders:
- `data` with CSVs containing the data
- `results` with results and images generated from the data, and also sources (SVG) for any images in the paper
- `src` with scripts and Jupyter Notebooks used to get, explore, analyze and visualize data

## Requirements

- Install [conda](https://conda.io/miniconda.html)

    ```
    $ make install-conda
    ```

- Create the conda environment

    ```
    $ make create-env
    ```

## Explore and visualize data

Jupyter Notebooks have been used to generate the graphs for the paper. They are stored in the `src` folder

### Usage

- Launch [Jupyter](https://jupyter.org/) to access the notebooks to generate graphs

    ```
    $ make run-jupyter
    ```

    If you plan to run the publication notebook, before launching it:
    
    1. Create a [Zotero API key](https://www.zotero.org/settings/keys/new)
    2. Export the key as an environment variable: `$ export ZOTERO_API=<your_key>`

- Go to [http://localhost:8888](http://localhost:8888) (a page should open automatically in your browser)
- Open the interesting notebook
- Make changes and save them


