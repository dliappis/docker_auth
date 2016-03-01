FROM busybox
COPY ca-bundle.crt /etc/ssl/certs/ca-certificates.crt
COPY auth_server .
EXPOSE 7000
ENTRYPOINT ["/auth_server"]
CMD ["/config/auth_config.yml"]
