pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
               sh "chmod +x ./script.sh"
                sh "./script.sh"
           }
        }  
    }
}
