pipeline {
    agent { dockerfile true {
        dir 'app'
        label 'pixi docker'}
          }
    stages {
        stage('Build') {
            steps {
                echo "hello"
            }
        }
    }
}
