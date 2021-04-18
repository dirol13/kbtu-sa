FROM scratch
WORKDIR /app
COPY /app/main /app/main
COPY templates/* /app/templates/
COPY zoneinfo.zip /
ENV TZ=Asia/Almaty
ENV ZONEINFO=/zoneinfo.zip
ENTRYPOINT ["/app/main", "-profile", "docker"]