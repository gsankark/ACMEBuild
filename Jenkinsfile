pipeline {
    agent any
    stages{
        stage ('Gokul') {
            steps {
                git 'https://github.com/gsankark/ACMEBuild'
            }
        }
        stage ('Sankar') {
            steps {
                bat label: '', script: 'mvn clean install'
            }
        }
    }
}
