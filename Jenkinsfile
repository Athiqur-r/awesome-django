pipeline {
     agent any
     environment {
        CI = 'true'
     }
     stages {
        stage("Build") {
            steps {
                sh "pip install"
                sh "python manage.py runserver" 
            }
        }
    }
}
