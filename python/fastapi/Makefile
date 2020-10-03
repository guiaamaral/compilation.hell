all: docker run
docker:
	docker build -t guiaamaral/python-fastapi-hello-world:latest ./
run:
	docker run -p 80:80 guiaamaral/python-fastapi-hello-world:latest