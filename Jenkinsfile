pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                bat '"C:\\Program Files\\Apache\\Maven\\apache-maven-3.9.14\\bin\\mvn.cmd" clean compile'
            }
        }

        stage('Test') {
            steps {
                bat '"C:\\Program Files\\Apache\\Maven\\apache-maven-3.9.14\\bin\\mvn.cmd" test'
            }
        }

        stage('Package') {
            steps {
                bat '"C:\\Program Files\\Apache\\Maven\\apache-maven-3.9.14\\bin\\mvn.cmd" package'
            }
        }
    }
}