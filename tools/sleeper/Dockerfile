FROM centos

RUN yum -y update && yum -y install iproute bind-utils && yum clean all

CMD ["/bin/bash", "-c", "echo Sleeping...; trap : TERM INT; sleep 365d & wait"]
