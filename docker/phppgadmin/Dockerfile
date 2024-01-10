FROM dockage/phppgadmin:latest

COPY ./phpPgAdmin-7.13.0/. /var/www/.
COPY --from=postgres:alpine /usr/local/bin/. /usr/bin/.

EXPOSE 80