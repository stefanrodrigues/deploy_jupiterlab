FROM quay.io/jupyter/pyspark-notebook

ENV CHOWN_HOME=yes
ENV CHOWN_HOME_OPTS='-R'

# By default, listen on port 8081
EXPOSE 8888/tcp
EXPOSE 4040/tcp
EXPOSE 4041/tcp

# Teste RUN
RUN chgrp -R 0 /home/jovyan && \
    chmod -R g=u /home/jovyan
