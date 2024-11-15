FROM python:3.9-slim 

WORKDIR /app 

COPY . /app 

RUN pip install --no-cache-dir -r req.txt 

EXPOSE 5000
EXPOSE 80

CMD ["python", "app.py"]
