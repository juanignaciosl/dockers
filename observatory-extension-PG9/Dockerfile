FROM carto/bigmetadata_postgres
 
RUN apt-get -y update

COPY pg_hba.conf /etc/postgresql/9.5/main/
RUN chown postgres:postgres /etc/postgresql/9.5/main/pg_hba.conf
RUN chmod 0400 /etc/postgresql/9.5/main/pg_hba.conf
