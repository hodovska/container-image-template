.PHONY: doc run build test

VERSION ?= x.y

doc:
	cd fedora && make doc VERSION=$(VERSION)
	cd centos && make doc VERSION=$(VERSION)
	cd rhel && make doc VERSION=$(VERSION)	

run:
	cd fedora && make run VERSION=$(VERSION)
	cd centos && make run VERSION=$(VERSION)
	cd rhel && make run VERSION=$(VERSION)

build:
	cd fedora && make build VERSION=$(VERSION)
	cd centos && make build VERSION=$(VERSION)
	cd rhel && make build VERSION=$(VERSION)

test:
	cd fedora && make test VERSION=$(VERSION)
	cd centos && make test VERSION=$(VERSION)
	cd rhel && make test VERSION=$(VERSION)
