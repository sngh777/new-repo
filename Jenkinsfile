pipeline {
    agent any

    stages {
        stage('SCM Checkout'){
              steps {
                git branch: 'main', url: 'https://github.com/sngh777/new-repo.git'
            }
        }
        stage('Hello') {
            steps {
                bash scipt.sh
            }
        }
    }
}
