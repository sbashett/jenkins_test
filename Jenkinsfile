
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'ls -a'
                sh '''
                    echo "multi line test"
                    ls -hls
                    cat /etc/os-release
                    '''
            }
        }
    }
}

