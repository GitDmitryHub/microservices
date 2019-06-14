FROM python:3.6.0-alpine
RUN pip install --upgrade pip && pip install flask pymongo 
WORKDIR /app
ADD . /app
ENV POST_DATABASE_HOST pst_db
ENV POST_DATABASE psts
ENTRYPOINT ["python3", "post_app.py"]
