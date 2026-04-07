FROM ibmjava:8-jre

WORKDIR /app

COPY . /app/

RUN chmod +x /app/AgenciesBackOnTrack/AgenciesBackOnTrack_run.sh

ENTRYPOINT ["/bin/sh", "/app/AgenciesBackOnTrack/AgenciesBackOnTrack_run.sh"]