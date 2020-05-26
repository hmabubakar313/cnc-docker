FROM python:3.8-slim
WORKDIR /app
ADD . /app
RUN pip install --trusted-host pypi.python.org Flask
ENV BGNAME=purple
EXPOSE 4000
CMD ["python","app.py"]
