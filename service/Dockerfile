FROM fedora:28

RUN dnf install -y python-qpid-proton && dnf clean all -y
ADD service /
ENTRYPOINT ["/service"]
