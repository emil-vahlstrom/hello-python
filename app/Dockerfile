FROM python:3.7

RUN mkdir /app
WORKDIR /app
ADD ./app /app/
RUN pip install -r ./app/requirements.txt

RUN ls -la /app
RUN ls -la /.
RUN ls -la ./app

EXPOSE 5000
CMD ["python", "/app/main.py"]

