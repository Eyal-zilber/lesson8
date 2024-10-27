pipeline {
    agent any

    environment {
        PYTHON_HOME = 'C:\\Users\\Eyal\\AppData\\Local\\Microsoft\\WindowsApps\\python.exe'
        PATH = "${env.PYTHON_HOME};${env.PATH}"
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('run') {
            steps {
                bat 'python lesson8_click.py'
            }
        }
    }
}
