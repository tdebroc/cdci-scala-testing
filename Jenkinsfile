pipeline {
    agent any

     parameters {
        string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
    }

    stages {
        stage('Hello') {
            steps {
                echo '${params.Greeting} World'
            }
        }
        stage('Hello2') {
            steps {
                echo "${params.Greeting}"
            }
        }
        stage('Hello3') {
            steps {
                echo 'bonjour'
            }
        }
    }
}
