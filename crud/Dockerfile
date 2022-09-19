FROM python:3.9

WORKDIR /usr/src/crud

COPY ./requirements.txt .

RUN pip install -r requirements.txt

COPY . .

CMD python manage.py migrate
