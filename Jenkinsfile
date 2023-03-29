pipeline {
    agent any
    
    environment{
     BRANCH='main'   
    }
    
    stages {
        stage('Checkout code from git'){
                    steps{
                        git 'https://github.com/ShubhamDiwan/Git_Jenkins_demo.git'
                    }
                }
        stage(' Java Version') {
                    steps {
                        sh 'java --version'
                    }
                }
    }
}
