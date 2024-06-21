FROM python:3.12.4-alpine3.20
ADD app.py requirements.txt code/
WORKDIR /code
RUN pip install -r requirements.txt
CMD ["python", "app.py"]