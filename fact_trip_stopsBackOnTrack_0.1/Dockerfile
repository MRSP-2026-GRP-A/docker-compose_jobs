FROM ibmjava:8-jre

WORKDIR /app

COPY . /app/

RUN chmod +x /app/fact_trip_stopsBackOnTrack/fact_trip_stopsBackOnTrack_run.sh

ENTRYPOINT ["/bin/sh", "/app/fact_trip_stopsBackOnTrack/fact_trip_stopsBackOnTrack_run.sh"]