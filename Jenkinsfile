pipeline {
    agent any
    stages {
        stage('Local Directory Cloning') {
            steps {
                bat 'xcopy /S "*" "C:/xampp/htdocs/practical5\" /Y /I'
            }
        }
        stage('Confirm') {
            steps {
                echo 'Done!'
            }
        }
    }
}
