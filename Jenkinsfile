pipeline {
    agent any   

    stages {
        stage ("Docker-build") {
            steps {
                sh "docker build -t ash2code/todo-app ."
            }
        } 
    }
}
