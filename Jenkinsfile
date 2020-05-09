pipeline {
      agent any
      stages {
            stage('Build stage') {
                  steps {
                        echo 'Code build is completed'
                        echo 'unit test is also performed'
                  }
            }
            stage('Test build') {
                  steps {
                        echo 'Test build : functional,non functional,regression and performance'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
			stage('Deploy to production') {
                  steps {
                        echo "Deploying to produnction"
                  }
            }
            
      }
}