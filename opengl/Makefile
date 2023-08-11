# build & test automation
APP_NAME=myLine


all: build
	./${APP_NAME}

build:
	g++ ${APP_NAME}.cpp -o ${APP_NAME} -lglut -lGLU -lGL

clean:
	rm -rf *.o ${APP_NAME}
