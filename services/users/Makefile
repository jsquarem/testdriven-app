excludes = \*~ \*.pyc .cache/\* test_\* __pycache__/\*

.PHONY: clean
clean:
	find . -type f -name '*.pyc' -delete

.PHONY: build
build:
	docker-compose up --build