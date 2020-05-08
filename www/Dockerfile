FROM busybox:latest
COPY website/public /srv
EXPOSE 80
CMD ["/bin/httpd", "-f", "-h", "/srv"]
