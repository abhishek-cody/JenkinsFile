pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post {
      success {
            echo "hehehe"
         // emailext body: 'Hello abhishek your jenkins job is running successfully ', subject: 'Testing for email sending by Jenkins', to: 'asabhisheksharma91@gmail.com'
      }
    }
}
