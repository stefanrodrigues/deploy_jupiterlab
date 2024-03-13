FROM quay.io/jupyter/pyspark-notebook

# By default, listen on port 8081
EXPOSE 8888/tcp
EXPOSE 4040/tcp
EXPOSE 4041/tcp

RUN chgrp -R 0 /home/jovyan/notebooks && \
    chmod -R g=u /home/jovyan/notebooks
