pipeline{
    agent any
    
    tools{nodejs "node"}
    
    stages{
        stage('Build'){
            steps{
                git branch: 'main', url: 'https://github.com/vikashchaudhary16/ssr-demo.git'
                bat 'npm install'
            }
        }
    }
}