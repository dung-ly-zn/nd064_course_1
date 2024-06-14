FROM python:3.8

WORKDIR .

EXPOSE 3111
RUN pip install -r ./requirements.txt
RUN python3 ./init_db.py

# command to run on container start
CMD [ "python", "./app.py" ]
