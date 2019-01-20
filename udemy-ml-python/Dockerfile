# minimal-notebook image as of 20190109
FROM jupyter/base-notebook:87210526f381

COPY requirements.txt /tmp/
RUN pip install --requirement /tmp/requirements.txt 
COPY . /tmp/