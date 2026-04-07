FROM ibmjava:8-jre

WORKDIR /app

COPY . /app/

RUN chmod +x /app/dim_stopBackOnTrack/dim_stopBackOnTrack_run.sh

ENTRYPOINT ["/bin/sh", "/app/dim_stopBackOnTrack/dim_stopBackOnTrack_run.sh"]