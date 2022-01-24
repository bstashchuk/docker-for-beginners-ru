FROM python:alpine

WORKDIR /app

RUN pip install pymongo

COPY . .

CMD [ "python", "main.py" ]