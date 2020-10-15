FROM rundeck/rundeck:3.3.2

COPY --chown=rundeck:root ./libext ./libext

USER root
RUN apt update && apt install -y awscli

COPY rundeck-config.properties /etc/remco/templates/