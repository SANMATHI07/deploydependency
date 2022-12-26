pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
               sh "chmod +x ./dep.sh"
                sh "./"
           }
        }  
    }
}
