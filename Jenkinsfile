pipeline {
    agent {
      node {label 'practice'}

    }

    stages {


        stage('build') {
            steps {
                sh 'npm install'
            }
        }

        stage('unit tests') {
           steps {
                echo 'unit tests'
                // sh 'npm test'
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