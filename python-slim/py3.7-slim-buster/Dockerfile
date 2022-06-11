FROM python:3.7-slim-buster

# ADD Python dependencies
COPY ./requirements.txt /requirements.txt
RUN pip3 install --no-cache-dir -r /requirements.txt

# Deploy node
# COPY start-spark.sh /
# CMD ["/bin/bash", "/start-spark.sh"]