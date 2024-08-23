FROM python:3.11

WORKDIR /app

COPY . .

RUN pip install poetry && poetry install --no-dev 

CMD ["python", "-m", "personal_assistant"]
