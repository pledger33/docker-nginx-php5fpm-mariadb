pipeline {
    agent any
    parameters {
        string(name: 'PERSON', defaultValue: 'Mr Pareil', description: 'Qui êtes vous')
    }
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON} , vous avez été reconnu"
            }
        }
    }
}
