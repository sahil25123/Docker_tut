#pull a base image which gives all the req. tools and lib 
FROM openjdk:17-jdk-alpine 

#create a folder where the app code will be stored
WORKDIR /app

#copy the source code from your host machone to your container
COPY Main.java  /app/Main.java

#compile the application code
RUN javac Main.java

#run the application
CMD ["java" , "Main"]