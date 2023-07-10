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

        stage('build') {
            steps {
                 echo 'build'
            }
        }

        stage('unit tests') {
           steps {
                echo 'unit tests'
           }
        }

        stage('code analysis') {
           steps {
               echo 'code analysis'
           }
        }

        stage('Security Scans') {
           steps {
               echo 'Security Scans'
           }
        }

        stage('publish a artifact') {
           steps {
               echo 'publish a artifact'
           }
        }
    }
}