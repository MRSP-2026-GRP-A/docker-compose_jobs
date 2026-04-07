FROM ibmjava:8-jre

WORKDIR /app

COPY . /app/

RUN chmod +x /app/dim_routesBackOnTrack/dim_routesBackOnTrack_run.sh

ENTRYPOINT ["/bin/sh", "/app/dim_routesBackOnTrack/dim_routesBackOnTrack_run.sh"]