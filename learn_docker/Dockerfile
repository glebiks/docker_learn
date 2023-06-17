FROM python:3.10

ENV PYTHONUNBUFFERED = 1

WORKDIR /code

COPY req.txt .

RUN pip install -r req.txt

COPY . .

EXPOSE 8000

CMD ["python", "manage.py", "runserver"]