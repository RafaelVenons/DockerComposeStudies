FROM python:3
WORKDIR /app
COPY ./src/requirements.txt .
RUN pip install -r requirements.txt
COPY ./src/ .
ENV FLASK_APP=app.py
EXPOSE 5000
CMD ["flask", "run", "--host", "0.0.0.0"]
