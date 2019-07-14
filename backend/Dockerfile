FROM python:3
RUN mkdir /backend
WORKDIR /backend
COPY requirements.txt /backend/
RUN pip install -r requirements.txt
COPY . /backend/
COPY uwsgi.ini /backend/
EXPOSE 8000