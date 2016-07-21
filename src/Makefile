
TAG = v3.1.0-1

all: container

container:
	docker build -t $(PREFIX)/heapster_grafana:$(TAG) .

push:
	docker push $(PREFIX)/grafana:$(TAG)


