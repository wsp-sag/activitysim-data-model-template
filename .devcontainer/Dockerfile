FROM mcr.microsoft.com/vscode/devcontainers/anaconda

COPY environment.yml /tmp/conda-tmp/
RUN /opt/conda/bin/conda env update -n base -f /tmp/conda-tmp/environment.yml
