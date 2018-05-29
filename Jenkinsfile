pipeline {
    agent any
    parameters {
        string(name: 'PERSON', defaultValue: 'Mr Pareil', description: 'Je suis là baby !')
    }
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.PERSON}"
            }
        }
    }
}
