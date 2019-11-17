FROM busybox:latest
COPY site /srv
EXPOSE 80
CMD ["/bin/httpd", "-f", "-h", "/srv"]
