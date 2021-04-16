FROM nvcr.io/nvidia/pytorch:21.03-py3
LABEL maintainer="ruddyscent@gmail.com"
RUN apt-get update && apt-get install -y swig xvfb python-opengl x11-apps
RUN pip install gym box2d-py ipywidgets gym-notebook-wrapper

