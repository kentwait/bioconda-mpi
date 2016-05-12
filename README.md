# anaconda-mpi

Docker container for developing MPI applications in Python using Jupyter notebook.
Includes a full installation of Anaconda 2.5.0 for Python 3.5.

## Install

	docker pull kentwait/anaconda-mpi

## Usage

The following command runs the container which launches a Jupyter notebook running Python 3.5 and IPython 4.1.1.

	docker run -d -p <port>:8888 -v <directory>:/home/docker/notebooks kentwait/anaconda-mpi

Replace `<port>` with 8888 (default) or any unused port on the host machine.
Replace `<directory>` with the directory where notebooks will be stored on the host machine.
