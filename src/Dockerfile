FROM python:3.12

ADD . /src
WORKDIR /src

# add and install requirements
ADD requirements.txt requirements.txt
RUN pip install -r requirements.txt

ENV FLASK_APP=./app.py
ENV PYTHONPATH="${PYTHONPATH}:/src"

# flask run
EXPOSE 5000
CMD ["flask", "run", "--host", "0.0.0.0"]
