FROM python:3

ENV PYTHONUNBUFFERED=1

WORKDIR /app

COPY . .

RUN python -m pip install --upgrade pip

RUN pip install -r requirements.txt

EXPOSE 8000

CMD [ "sh", "script.sh"]