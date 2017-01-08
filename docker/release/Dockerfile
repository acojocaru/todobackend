FROM acojocaru/todobackend-base:latest
MAINTAINER Alexandru Cojocaru <cjcr_alexandru@yahoo.com>

COPY target /wheelhouse

RUN . /appenv/bin/activate && \
    pip install --no-index -f /wheelhouse todobackend && \
    rm -rf /wheelhouse
