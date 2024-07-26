FROM python:3.11.9
RUN pip install environs ls-trace pyyaml
ADD *.py /app/
CMD ["ls-trace-run", "/usr/local/bin/python", "/app/client.py"]
