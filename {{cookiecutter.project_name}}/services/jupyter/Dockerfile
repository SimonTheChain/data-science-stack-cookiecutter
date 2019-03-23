FROM jupyter/scipy-notebook

USER root

RUN pip install --proxy=${http_proxy}\
    psycopg2-binary\
    astropy\
    astroquery\
    astroplan\
    ipynb\
    minio

USER jovyan
