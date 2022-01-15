FROM pangeo/base-image:2021.09.30
RUN mkdir -p /home/jovyan/.config/dask/
RUN echo 'distributed:\n  dashboard:\n    link: "/proxy/localhost:8787"' >> /home/jovyan/.config/dask/distributed.yaml
RUN mamba install -c conda-forge graphviz
