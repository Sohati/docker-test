FROM python:3.9-slim
# ENV PYTHONDONTWRITEBYTECODE=1 \
#     PYTHONUNBUFFERED=1
RUN mkdir -p /app
WORKDIR /app   
COPY . /app
CMD ["python", "app.py"]      