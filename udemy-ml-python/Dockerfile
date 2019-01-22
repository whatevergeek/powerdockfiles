FROM continuumio/miniconda3
RUN conda create -n bostonhousingproject spyder
RUN conda install -c conda-forge jupyterlab  -n bostonhousingproject
RUN echo "source activate bostonhousingproject" > ~/.bashrc
ENV PATH /opt/conda/envs/bostonhousingproject/bin:$PATH
