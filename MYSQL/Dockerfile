FROM mysql:8.0 
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1
#warning sensitive data exposed here
#mysql -u root -p
COPY *.sql /docker-entrypoint-initdb.d


