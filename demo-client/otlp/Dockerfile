FROM python:3.14.0a3
RUN pip install opentelemetry-launcher requests pyyaml protobuf==3.13.0
RUN opentelemetry-bootstrap -a install

ADD client.py /app/client.py
CMD ["opentelemetry-instrument", "/app/client.py"]
