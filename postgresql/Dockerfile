FROM postgres:9.6.13
 
MAINTAINER Luiz Reis <dluiz.reis@pravaler.com.br>

#-----------------------------------------------------------------------------------------------#
# Ajusta a configuração do PostgreSQL para ser possível fazer conexão remota ao banco de dados. #
#-----------------------------------------------------------------------------------------------#
RUN echo "host all  all    0.0.0.0/0  md5" >> /var/lib/postgresql/data/pg_hba.conf

CMD ["postgres"]

EXPOSE 5432