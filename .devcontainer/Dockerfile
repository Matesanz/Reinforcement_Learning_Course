FROM jupyter/minimal-notebook:notebook-6.4.3

# Needed dependencies to run gym rendering
USER root
RUN apt-get update && apt-get install -y python-opengl graphviz xvfb
USER ${NB_USER}

# Install python dependencies
COPY requirements.txt requirements.txt
RUN conda install --file requirements.txt
