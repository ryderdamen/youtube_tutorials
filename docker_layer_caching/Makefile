IMAGE_NAME=docker_layer_cache_example

.PHONY: build
build:
	@docker build -t $(IMAGE_NAME) .

.PHONY: run
run:
	@docker run -p 5000:5000 $(IMAGE_NAME)
