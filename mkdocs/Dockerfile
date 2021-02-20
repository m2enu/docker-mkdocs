FROM python:3.9.1-slim-buster

RUN mkdir /docs
WORKDIR /docs

RUN pip install --upgrade pip && pip install \
    mkdocs \
    mkdocs-material

CMD ["mkdocs", "serve", "--dev-addr=0.0.0.0:8000"]
