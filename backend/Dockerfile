FROM python:3.9.13
LABEL author ="fauzi"
WORKDIR /app
COPY ./requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY . .
ENTRYPOINT ["python3"]
CMD ["app.py"]