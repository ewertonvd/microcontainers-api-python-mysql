FROM python:2

MAINTAINER Ewerton Vieira Donati <ewertonvd@gmail.com>

ADD api.py requirements.txt /
RUN pip install -r ./requirements.txt

ENV PORT=5000

EXPOSE $PORT
HEALTHCHECK CMD curl --fail http://localhost:$PORT || exit 1

RUN chmod +x api.py

CMD [ "./api.py" ]
