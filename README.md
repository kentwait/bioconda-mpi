# bioconda-mpi

Docker container for developing bioinformatics applications in Python using Jupyter notebook.
Based on anaconda-mpi which includes a full installation of Anaconda 2.5.0 for Python 3.5, but
includes additional packages for bioinformatics and computational biology projects.

## Install

	docker pull kentwait/bioconda-mpi

## Usage

The following command runs the container which launches a Jupyter notebook running Python 3.5 and IPython 4.1.1.

	docker run -d -p <port>:8888 -v <directory>:/home/docker/notebooks kentwait/bioconda-mpi

Replace `<port>` with 8888 (default) or any unused port on the host machine.
Replace `<directory>` with the directory where notebooks will be stored on the host machine.
