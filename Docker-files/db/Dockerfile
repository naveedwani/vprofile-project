FROM mysql:8.0.33
LABEL PROJECT="Vprofile"
LABEL Author="Naveed"
ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQ_DATABASE="accounts"
ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql