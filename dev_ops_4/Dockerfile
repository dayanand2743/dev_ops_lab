FROM python:3.8-slim

WORKDIR /app

COPY . /app

# Debug: List files in /app directory
RUN ls -alh /app

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 15000

CMD ["python", "app.py"]
