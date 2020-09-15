# cicd-pipeline-train-schedule-docker

This is a simple train schedule app written using nodejs. It is intended to be used as a sample application for a series of hands-on learning activities.

## Build a Docker image of this app with the dockerfile

    sudo docker build -t <your username>/train-schedule .
    
Run a container of the image 

    sudo docker run -p 8080:8080 -d <your username>/train-schedule
 
Once the container is running, you should be able to access the train schediule app in a browser at: 

http://(your learning activity environment public IP):8080

## Running the app

You need a Java JDK 7 or later to run the build. You can run the build like this:

    ./gradlew build

You can run the app with:

    ./gradlew npm_start

Once it is running, you can access it in a browser at http://localhost:8080
