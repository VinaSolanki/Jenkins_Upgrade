pipeline {
      agent any
      stages {
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Dev') {
                  steps {
                        echo 'Deploying in Dev Area'
                  }
            }
            stage('Test') {
                  steps {
                        echo "Deploying in Test Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}
