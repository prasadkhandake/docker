FROM python:3.8-slim 
COPY . /app
COPY requirements.txt .
WORKDIR /app
RUN pip install -r requirements.txt
CMD python app.py