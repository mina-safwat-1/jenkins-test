pipeline {
    agent any
    environment {
        name = credentials("name")
        country ="egypt"
    }


    stages {
        stage("test jenkins") {


        
    
        steps {
            
            withCredentials([usernamePassword(credentialsId: 'jenkins', usernameVariable: 'name', passwordVariable: 'password')]) {
                sh "echo ${name} ${password}"

            }
        }
        }
    }
}