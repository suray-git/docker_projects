FROM python:latest
LABEL MAINTAINER surendhar <surendhar.muruganandam@gmail.com>
WORKDIR /usr/src/app
COPY requirements.txt  .
RUN pip install -r requirements.txt
COPY app.py  .
EXPOSE 80
CMD ["python", "app.py"]
