pipeline {
    agent any

    stages { 
        stage('Create Directories') {
            steps {
                sh '''
                    mkdir -p freezo
                '''
            } 
        }

        stage('Create File') {
            steps {
                sh '''
                    cd freezo
                    touch fridade
                '''
            } 
        }
    }
}
