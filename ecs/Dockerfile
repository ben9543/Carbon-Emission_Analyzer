# syntax=docker/dockerfile:1

FROM python:3.10.5-alpine3.16

RUN python -m pip install boto3 && python -m pip install requests && python -m pip install netCDF4

WORKDIR /scripts

COPY . .

CMD python3 main.py 