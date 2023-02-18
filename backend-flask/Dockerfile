FROM python:3.10-slim-buster

#Inside container
#make new folder
WORKDIR /backend-flask
#Outside container -> Inside container
COPY requirements.txt requirements.txt
#Inside container
#Install the python libriries used for the app
RUN pip3 install -r requirements.txt
#Outside container -> Inside container
#means everything in the current directory
COPY . .
#Set environment variables
#Inside container
ENV FLASK_ENV=development

EXPOSE ${PORT}
#Command python3 -m flask run --host=0.0.0.0 --port=4567
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]