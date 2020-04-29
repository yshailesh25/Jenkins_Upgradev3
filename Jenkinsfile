pipeline {
      agent any
      stages {
            stage('Build stage') {
                  steps {
                        print 'Code build is completed'
                        print 'unit test is also performed'
                  }
            }
            stage('Test build') {
                  steps {
                        print 'Test build : functional,non functional,regression and performance'
                  }
            }
            stage('Deploy') {
                  steps {
                        print "Deploying in Staging Area"
                  }
            }
			stage('Deploy to production') {
                  steps {
                        print "Deploying to produnction"
                  }
            }
            
      }
}