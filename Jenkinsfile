pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/sngh777/new-repo.git'
            }
            steps {
                bash scipt.sh
            }
        }
    }
}
