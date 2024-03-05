pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build'
                sh '''
                echo ${BUILD_NUMBER}
                ls
                '''
            }
        }
    }

    options {  
        timeout { time: 30, unit: 'SECONDS' }
    }
}


