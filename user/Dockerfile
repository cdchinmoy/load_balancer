# using a python small basic image
FROM python:3.9.5-slim
RUN mkdir -p /usr/src/app
# creates a dir for our application
WORKDIR /usr/src/app
# copy our requirements.txt file and install dependencies
COPY requirements.txt .
RUN pip install -r requirements.txt
# copy the rest of our application
COPY . .