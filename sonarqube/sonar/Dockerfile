FROM sonarqube:lts-community
EXPOSE 9000
USER root
RUN groupadd sonar
RUN  useradd -rm -d /home/sonar -s /bin/bash -g sonar -u 1001 sonar
RUN chown -R sonar:sonar /opt/sonarqube/
USER sonar
