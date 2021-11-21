ARG BASE_PRIVATE_REGISTRY=""
FROM ${BASE_PRIVATE_REGISTRY}jupyterhub/jupyterhub:1.5.0
LABEL maintainer="yehiyam@gmail.com"
RUN adduser hkube
RUN pip install notebook===6.4.5
COPY jupyterhub_config.py /srv/jupyterhub/jupyterhub_config.py