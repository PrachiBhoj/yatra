pipeline {
    agent none
    stages {
        stage('Example Build') {
            agent { docker 'maven:3.8.6-adoptopenjdk-11' }
            steps {
                echo 'Hello, Maven'
                sh 'mvn --version'
            }
        } pipeline {
    agent none
    stages {
        stage('Example Build') {
            agent { docker 'maven:3.8.6-adoptopenjdk-11' }
            steps {
                echo 'Hello, Maven'
                sh 'mvn --version'
            }
        }
        stage('Example Test') {
            agent { docker 'openjdk:8-jre' }
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
    }
}
        stage('Example Test') {
            agent { docker 'openjdk:8-jre' }
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
    }
}



