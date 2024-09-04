pipeline {
    agent any 

    environment {
        DOCKER_UID = "ash2code"
    }  

    stages {
        stage ("Docker-build") {
            steps {
                sh "docker build -t ${DOCKER_UID}/todo-app ."
            }
        } 
    }
}
