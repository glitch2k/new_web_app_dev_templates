FROM python:3.8


RUN adduser --home /home/app app

USER app
WORKDIR /home/app


COPY . . 

RUN pip install -r requirements.txt

ENTRYPOINT [ "python" ]
CMD [ "app.py" ]