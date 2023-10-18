pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Welcome to Jenkins Enviroment"
                sh 'echo second step'
                sh 'echo another step'                
                sh '''
                echo 'Multiline'
                echo 'Example'
                '''
                echo 'not using shell'
            }
        }
        stage('push images') {
            steps {
                echo "This will push the images"
                sh 'echo second step'
                sh 'echo another step'                
                sh '''
                echo 'Multiline'
                echo 'Example'
                '''
                echo 'not using shell'
            }
        }
        stage('deploy') {
            steps {
                echo "This will run the application"
                sh 'echo second step'
                sh 'echo another step'                
                sh '''
                echo 'Multiline'
                echo 'Example'
                '''
                echo 'not using shell'
            }
        }


    }
}
