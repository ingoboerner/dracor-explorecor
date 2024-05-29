# CLS INFRA Training School: ExploreCor – Using Programmable Corpora in Computational Literary Studies

Vienna 10-14 June 2024

https://clsinfra.io/events/training-school/

This repository contains the teaching material used for the **DraCor-related sessions** of the CLS INFRA Training School: *ExploreCor – Using Programmable Corpora in Computational Literary Studies*.

The following sessions are covered by this material:

- 1. Introduction to Programmable Corpora
- 2. Corpora in CLS Research
- 5. Exploring Programmable Corpora (Focus: Network Analysis)
- 6. Reproducibility in CLS Research
- 7. Deepen

## Setup of a Local DraCor Environment
You can setup a local DraCor infrastructure and run the provided Jupyter notebooks in your local Jupyter Lab instance. We provide a Docker Compose File that can be used to start the services. It is necessary to have Git and Docker (Desktop) installed. If you are working on Windows use the Windows Powershell to execute the commands below:

1. In your Terminal clone this repository with the command `git clone https://github.com/dracor-org/dracor-explorecor.git`. Alternatively you can [download](https://github.com/dracor-org/dracor-explorecor/archive/refs/heads/main.zip) and unpack the ZIP file. 
2. Change into the folder `dracor-explorecor` with the command `cd dracor-explorecor`
3. Use the command `docker compose up` to start the Docker container
4. Navigate to [http://localhost:8889](http://localhost:8889) to access your local Jupyter Lab instance containing the materials.

## Build a Jupyter Book (optional)
You can build a HTML version of the teaching materials: Inside the Docker Container (e.g. from a Terminal Tab in Jupyter Lab) navigate to the `notebooks` folder and build the book with `jupyter-book build .`. You will find a directory `_build` containing the HTML version in the `dracor-explorecor` folder on your machine.

