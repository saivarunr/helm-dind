FROM lwolf/helm-kubectl-docker:v1103_291
RUN apk add --update python3 python3-dev py-pip curl
RUN curl --silent --location "https://github.com/weaveworks/eksctl/releases/download/latest_release/eksctl_$(uname -s)_amd64.tar.gz" | tar xz -C /tmp
RUN mv /tmp/eksctl /usr/local/bin
RUN python3 -m pip install awscli