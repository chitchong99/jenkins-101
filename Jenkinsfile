pipeline {
    agent { 
        node {
            label ''
            }
      }
    triggers {
        pollSCM '* * * * *'
    }
    stages {
        stage('Build') { 
            steps {
                echo "Building.."
                sh '''
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                python3 helloworld.py
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}
