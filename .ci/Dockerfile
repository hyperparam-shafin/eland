ARG PYTHON_VERSION=3.7
FROM python:${PYTHON_VERSION}

WORKDIR /code/eland
COPY requirements-dev.txt .
RUN pip install -r requirements-dev.txt

COPY . .


