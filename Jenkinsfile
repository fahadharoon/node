pipeline {
    agent none
    stages {
        stage('Test on Windows') {
            agent {
                label 'windows'
            }
            steps {
                bat '''
                    git clone https://github.com/fahadharoon/node.git;
                    dir
                '''
            }
        }
    }
}
