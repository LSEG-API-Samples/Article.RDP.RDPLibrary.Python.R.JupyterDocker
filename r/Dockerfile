# Start from a core stack version
FROM jupyter/r-notebook:70178b8e48d7

LABEL maintainer="Data Scientists <email>"

# Install package
RUN R -e "install.packages('plotly', repos='http://cran.rstudio.com/')"

ENV JUPYTER_ENABLE_LAB=yes
