FROM python:3.8-slim-buster
ENV PYTHONUNBUFFERD=1
WORKDIR /backend
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]