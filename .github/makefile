IMAGE-NAME := nginx
IMAGE-TAG := 1.0

docker-build:
        @ docker build -t ${IMAGE-NAME}:${IMAGE-TAG} .

docker-run:
        @ docker run ${IMAGE-NAME}:${IMAGE-TAG}

docker-login:
        @ docker login

docker-push:
        @ docker push ${IMAGE-NAME}:${IMAGE-TAG}
