build:
	docker build -t react-app:dev .

run:
	docker run -it --rm -v ${PWD}:/app -v /app/node_modules -p 3000:3000 -e CHOKIDAR_USEPOLLING=true react-app:dev
