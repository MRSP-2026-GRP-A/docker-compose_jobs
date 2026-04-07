FROM ibmjava:8-jre

WORKDIR /app

COPY . /app/

RUN chmod +x /app/fact_calendarBackOnTrack/fact_calendarBackOnTrack_run.sh

ENTRYPOINT ["/bin/sh", "/app/fact_calendarBackOnTrack/fact_calendarBackOnTrack_run.sh"]