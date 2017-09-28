# python:alpine is 3.{latest}
FROM python:alpine 

# Install Flask server
RUN pip install flask 

# Copy local directory "src" to container filesystem "/src"
COPY src /src

EXPOSE 80

ENTRYPOINT ["python", "/src/main.py"]
