pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
              
                git 'pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
              
                git 'https://github.com/chhayasingh0112/Frontend_devops_project.git'
            }
        }
        
        stage('Dockerize') {
            steps {
                
                sh 'docker build -t chaya01/frontend-app1 .'
               
            }
        }
        
        stage('Push to Docker Hub') {
            steps {
              
                sh 'docker login -u chaya01 -p Riya@0112'
             
                
                sh 'docker push chaya01/frontend-app1'
             
            }
        }
    }
}
'
            }
        }
        
        stage('Dockerize') {
            steps {
                
                sh 'docker build -t chaya01/frontend-app1 .'
               
            }
        }
        
        stage('Push to Docker Hub') {
            steps {
              
                sh 'docker login -u chaya01 -p Riya@0112'
             
                
                sh 'docker push chaya01/frontend-app1'
             
            }
        }
    }
}
