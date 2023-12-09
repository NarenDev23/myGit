pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Check out your code from a Git repository
                git branch: 'main', url: 'https://github.com/NarenDev23/jenkins-repo.git'
            }
        }
        stage('Deploy to Nginx') {
             steps {
                // Copy your HTML application files to the Nginx web root directory
                sh 'cp -r * /usr/share/nginx/html/'
            }
            }
        }
    }
}
