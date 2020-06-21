FROM 7a4301c46b85
COPY . /tmp
WORKDIR /tmp
RUN mkdir /tmp/in && mkdir /tmp/out
ENTRYPOINT ["python","entrypoint.py", "/tmp/in", "/tmp/out"] 
