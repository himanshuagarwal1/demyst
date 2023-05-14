FROM python:3-alpine

COPY . /webapp
RUN pip3 install -r /webapp/requirements.txt
RUN chmod +x /webapp/main.py

WORKDIR /webapp
CMD /webapp/main.py
EXPOSE 5000
