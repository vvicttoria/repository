FROM python:3.11.1

EXPOSE 8000

WORKDIR /usr/src/app/
COPY requirements.txt /usr/src/app/
RUN apt install libpq-dev gcc -y
RUN pip3 install -r requirements.txt --no-cache-dir
COPY . /usr/src/app/


CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]