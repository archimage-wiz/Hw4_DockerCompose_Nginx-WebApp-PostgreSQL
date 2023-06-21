FROM python:3.9

WORKDIR /src
    
RUN apt update
RUN apt install mc -y

COPY . .

# ENV SECRET_KEY=KLFNR032048023OIJFAJFOJDWS$$$(^@#)
# ENV DEBUG=True
# ENV ALLOWED_HOSTS=*,web_app,0.0.0.0,127.0.0.0
# ENV DB_ENGINE=django.db.backends.postgresql
# ENV DB_NAME=netology_stocks_products
# ENV DB_HOST=posgres_db
# ENV DB_PORT=5432
# ENV DB_USER=postgres
# ENV DB_PASSWORD=111

RUN pip install -r requirements.txt
# RUN python3 manage.py migrate

EXPOSE 8000

# RUN python3 manage.py runserver 0.0.0.0:8000
# CMD [ "python3", "manage.py", "runserver", "0.0.0.0:8000"]
# CMD [ "python3", "manage.py", "migrate"]

