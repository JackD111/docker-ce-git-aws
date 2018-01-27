FROM docker:17.12.0-ce-git

ENV VERSION 1.14.32

RUN apk --no-cache add python3 && \
	pip3 install --upgrade pip setuptools && \
	pip3 --no-cache-dir install awscli==${VERSION} && \
	rm -rf /var/cache/apk/*
