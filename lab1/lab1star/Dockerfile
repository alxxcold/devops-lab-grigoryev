FROM python:3.9-slim

WORKDIR /app

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
    curl \
    vim

COPY . .

RUN pip install --no-cache-dir -r requirements.txt

RUN useradd -u 1000 flaskuser

USER flaskuser

EXPOSE 5000

ENV FLASK_ENV=production

CMD ["python", "app.py"]
