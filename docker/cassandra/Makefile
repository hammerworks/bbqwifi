VERSION=1.2.4
PROJECT=thingsboard
APP=cassandra

build:
	docker build --pull -t ${PROJECT}/${APP}:${VERSION} -t ${PROJECT}/${APP}:latest .

push: build
	docker push ${PROJECT}/${APP}:${VERSION}
    docker push ${PROJECT}/${APP}:latest