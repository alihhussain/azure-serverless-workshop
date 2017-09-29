# python:alpine is 3.{latest}
FROM python:alpine 

RUN pip install flask && pip install pymongo 

COPY src /src/

EXPOSE 80

ENTRYPOINT ["python", "/src/main.py"]
