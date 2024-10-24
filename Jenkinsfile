pipeline {
    agent any

    stages {
        stage('UnitTest') {
            steps {
              sh '''cd test_code
              ls -ltra
              python test_app.py
              '''
            }
        }
        stage('Read') {
            steps {
                 sh '''cd test_code
              cat sample_data.txt '''
            
            }
        }
  
    }
}
