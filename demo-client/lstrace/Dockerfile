FROM python:3.12.5
RUN pip install environs ls-trace pyyaml
ADD *.py /app/
CMD ["ls-trace-run", "/usr/local/bin/python", "/app/client.py"]
