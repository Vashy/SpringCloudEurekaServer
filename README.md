# Application Boot
Run the following command to build the docker image:

    docker build -t eureka-server:latest .

And then run it:

    docker run -it --rm -p 8761:8761 --net=spring-cloud-app --name=eureka-server eureka-server:latest

