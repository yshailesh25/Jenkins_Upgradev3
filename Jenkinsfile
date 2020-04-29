pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        print 'Hi, this is Anshul from LevelUp360'
                        print 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        print 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        print "Deploying in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        print "Deploying in Production Area"
                  }
            }
      }
}