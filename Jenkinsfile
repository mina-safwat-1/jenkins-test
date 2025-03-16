pipeline {
    agent any
    environment {
        name = credentials("name")
        country ="egypt"
    }


    stages {
        stage("test jenkins") {
        steps {
            echo "hello ${name} from ${country}"
        }
        }
    }
}