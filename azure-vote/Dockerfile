# Pull the base image
FROM tiangolo/uwsgi-nginx-flask:python3.6
# Install depndencies 
# RUN pip install redis
# RUN pip install opencensus
# RUN pip install opencensus-ext-azure
# RUN pip install opencensus-ext-flask
# RUN pip install opencensus-ext-logging
# RUN pip install flask

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

# Copy the content of the current directory to the /app of the container
ADD . /app
