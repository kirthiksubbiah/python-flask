pipeline {
    agent any
 
    stages {
        stage('Clone Code') {
            steps {
                git branch: 'main', // change to your actual branch name
                    url: 'https://github.com/kirthiksubbiah/python-flask.git',
                    credentialsId: 'github'
            }
        }
 
        stage('Run Script') {
            steps {
                echo 'Running your script...'
            }
        }
    }
}
