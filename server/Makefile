PYTHON_RUNTIME_TAG='helme/python-3.9'

python-build:
	docker build --tag ${PYTHON_RUNTIME_TAG} ./

update:
	git reset --hard
	git pull

start:
	docker-compose up -d

stop:
	docker-compose stop

clear:
	docker-compose down --volumes --rmi all