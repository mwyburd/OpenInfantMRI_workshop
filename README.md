# Applying Analysis To Open Datasets

This workshop demonstrates how to:

    1. Download publicly available MRI data from OpenNeuro

    2. Run BabySeg locally using Docker

    3. Visualise and inspect segmentation outputs

## Prerequisites
**Python IDE (recommended: VS Code)**

Participants should install a Python development environment (IDE) before the workshop. We recommend Visual Studio Code (VS Code), which provides an integrated terminal, notebook support, and a convenient interface for editing and running Python code.

Download VS Code:

Windows, Mac & Linux: https://code.visualstudio.com/

After installation, launch VS Code and verify that you can:

Open a folder on your computer
Open a terminal within VS Code
Run Python scripts and Jupyter notebooks

Other Python IDEs are also suitable (e.g., PyCharm, Spyder, JupyterLab), but the workshop materials and screenshots will use VS Code.

**Docker**

BabySeg is run inside a Docker container. Docker must be installed before the workshop.

Install Docker Desktop:

    - Windows & Mac: https://www.docker.com/products/docker-desktop/
    - Linux: https://docs.docker.com/engine/install/

After installation, open a terminal (for windows, open a terminal in Docker Desktop), and verify Docker is working using:

    ```bash
    docker run hello-world
    ```

You should see a message beginning with:

*Hello from Docker!*

## Download Workshop Materials

In VS Code (or an alternative interface), clone the repository by typing the following in a terminal. This should be in the directory where you want the workshop installed. For windows users type ``clone . `` in the Docker terminal to open VS Code.


    ```bash
    git clone <REPOSITORY_URL>
    cd OpenInfantMRI_workshop
    ```

or download the ZIP file from GitHub and extract it.


## Install Python Requirements

In VS Code (or an alternative interface), open a terminal and install the Python packages for the workshop:

    ```bash
    pip install -r requirements.txt
    ```
Or have VS Code make the environment for you by pointing to the repo.

## Start the workshop

Follow the guides in the notebooks:

    1. 01_Download_data.ipynb
    2. 02_install_babyseg.ipynb
    3. 03_run_babyseg_on_opendata.ipynb
