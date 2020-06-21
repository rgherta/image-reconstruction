FROM romangherta/openmvg
COPY . /tmp
WORKDIR /tmp
RUN mkdir /tmp/in && mkdir /tmp/out
ENTRYPOINT ["python","entrypoint.py", "/tmp/in", "/tmp/out"] 
