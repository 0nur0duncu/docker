FROM python:alpine

WORKDIR /usr/src/app

COPY requirenments.txt .

RUN pip install -r requirenments.txt
RUN rm requirenments.txt

COPY deneme.py .

ENTRYPOINT [ "python"] 
CMD ["deneme.py" ]