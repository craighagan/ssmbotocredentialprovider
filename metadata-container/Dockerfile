#https://blog.realkinetic.com/building-minimal-docker-containers-for-python-applications-37d0272c52f3
FROM python:3.6-alpine
RUN pip install --no-cache-dir ssmbotocredentialprovider>=1.0.1
EXPOSE 80
CMD ["python", "/usr/local/bin/fakemetadata-server.py", "--port", "80"]

