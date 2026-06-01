# Applying Analysis To Open Datasets

This workshop demonstrates how to:

    1. Download publicly available MRI data from OpenNeuro

    2. Run BabySeg locally using Docker

    3. Visualise and inspect segmentation outputs

## Prerequisites
**Docker**

BabySeg is run inside a Docker container. Docker must be installed before the workshop.

Install Docker Desktop:

    - Windows & Mac: https://www.docker.com/products/docker-desktop/
    - Linux: https://docs.docker.com/engine/install/

After installation, verify Docker is working:

    ```bash
    docker run hello-world
    ```

You should see a message beginning with:

*Hello from Docker!*

## Download Workshop Materials

Clone the repository:


    ```bash
    git clone <REPOSITORY_URL>
    cd OpenInfantMRI_workshop
    ```

or download the ZIP file from GitHub and extract it.


## Install Python Requirements

    ```bash
    pip install -r requirements.txt
    ```


## Start the workshop

Follow the guides in the notebooks:

    1. Download_data.ipynb
    2. install_babyseg.ipynb
    3. run_babyseg_on_opendata.ipynb