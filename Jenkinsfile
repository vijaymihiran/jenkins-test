pipeline {
    agent any


    environment {
        // def config = readJSON file: 'parameters.json'
        test = 'testing'
        work = 'working'

    }

    stages {

        stage('Install Node modules') {
            steps {
              sh   'echo "Running ENV"'
              sh '''
              chmod +x test.sh
              sh test.sh
              '''
            }
        }

}
