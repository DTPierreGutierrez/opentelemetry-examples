FROM python:3.14.0a2
RUN pip install environs ls-trace pyyaml
ADD *.py /app/
CMD ["ls-trace-run", "/usr/local/bin/python", "/app/client.py"]
