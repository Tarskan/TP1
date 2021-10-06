FROM python:2.7
LABEL maintainer="TP1"

COPY requirements.txt /usr/app/bin/

RUN pip install -r /usr/app/bin/requirements.txt

COPY app.py /usr/app/bin/

ENTRYPOINT ["app.py", "/usr/app/bin/app.py"]