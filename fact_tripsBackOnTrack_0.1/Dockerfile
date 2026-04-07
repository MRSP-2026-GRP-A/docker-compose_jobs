FROM ibmjava:8-jre

WORKDIR /app

COPY . /app/

RUN chmod +x /app/fact_tripsBackOnTrack/fact_tripsBackOnTrack_run.sh

ENTRYPOINT ["/bin/sh", "/app/fact_tripsBackOnTrack/fact_tripsBackOnTrack_run.sh"]