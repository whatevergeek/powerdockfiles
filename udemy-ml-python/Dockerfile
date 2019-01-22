FROM continuumio/miniconda3
RUN conda create -n bostonhousingproject python=3.6
RUN echo "source activate bostonhousingproject" > ~/.bashrc
ENV PATH /opt/conda/envs/bostonhousingproject/bin:$PATH