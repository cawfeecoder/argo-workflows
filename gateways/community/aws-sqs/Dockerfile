FROM arm64v8/centos:7
RUN yum -y install ca-certificates
COPY dist/aws-sqs-gateway /bin/
ENTRYPOINT ["/bin/aws-sqs-gateway"]
