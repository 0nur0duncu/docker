FROM python:alpine

WORKDIR /usr/src/app

COPY requirenments.txt .

RUN pip install -r requirenments.txt

RUN rm requirenments.txt

RUN pip list >> packages.txt

COPY flsk.py .

EXPOSE 5000

CMD python flsk.py