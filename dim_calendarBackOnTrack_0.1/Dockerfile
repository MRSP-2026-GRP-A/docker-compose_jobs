FROM ibmjava:8-jre

WORKDIR /app

COPY . /app/

RUN chmod +x /app/dim_calendarBackOnTrack/dim_calendarBackOnTrack_run.sh

ENTRYPOINT ["/bin/sh", "/app/dim_calendarBackOnTrack/dim_calendarBackOnTrack_run.sh"]