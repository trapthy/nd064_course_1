FROM python:3.14.0a4
LABEL maintainer="Katie Gamanji"

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt

# command to run on container start
CMD [ "python", "app.py" ]
