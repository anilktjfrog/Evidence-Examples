FROM python:3.7-slim-buster

WORKDIR /app

COPY ./examples/dependabot/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

CMD ["ansible", "--version"]