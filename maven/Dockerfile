FROM maven
RUN apt update
RUN apt install git -y
WORKDIR /app
RUN git clone https://github.com/joinfaces/joinfaces-maven-jar-example
WORKDIR /app/joinfaces-maven-jar-example
#RUN ls -lah
RUN mvn clean package