pipeline {
    agent any
 
    stages {
        stage('Clone Code') {
            steps {
                git branch: 'main', // change to your actual branch name
                    url: 'https://github.com/Santhosh2010-ramesh/First.git',
                    credentialsId: 'githubpat'
            }
        }
 
        stage('Run Script') {
            steps {
                echo 'Running your script...'
            }
        }
    }
}
