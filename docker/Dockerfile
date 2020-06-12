FROM coredns/coredns:latest

EXPOSE 53 53/udp
COPY Corefile /opt/Corefile
ENTRYPOINT ["/coredns","-conf","/opt/Corefile"]
