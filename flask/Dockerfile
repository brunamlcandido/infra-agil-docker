FROM python:alpine
EXPOSE 5000
WORKDIR /app
add . /app
RUN ["pip","install","-r","requirements.txt"]
ENTRYPOINT ["python"]
CMD ["app.py"]
