FROM python
EXPOSE 80

RUN pip3 install\
    django

WORKDIR /usr/src/app

COPY . .
CMD [ "python", "manage.py", "runserver", "0.0.0.0:80" ]
