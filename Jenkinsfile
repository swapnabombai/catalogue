pipeline {
    agent {
      node {label 'practice'}

    }

    stages {
        stage('code checkout') {
            steps {
                echo 'code checkout'
            }
        }
    stages {
        stage('build') {
            steps {
                 echo 'build'
            }
        }
    stages {
        stage('unit tests') {
           steps {
                echo 'unit tests'
           }
        }
    stages {
        stage('code analysis') {
           steps {
               echo 'code analysis'
           }
        }
    stages {
        stage('Security Scans') {
           steps {
               echo 'Security Scans'
           }
        }
    stages {
        stage('publish a artifact') {
           steps {
               echo 'publish a artifact'
           }
        }
    }
}