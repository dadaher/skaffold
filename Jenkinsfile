pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        echo 'Hello pipe'
        googlechatnotification(message: 'toto', url: 'titi', notifyAborted: true, notifyBackToNormal: true, notifyFailure: true, notifyNotBuilt: true, notifySuccess: true, notifyUnstable: true, sameThreadNotification: true, suppressInfoLoggers: true)
        hangoutsNotify(message: 'hangoutsNotify', token: 'FsFXssEpbV3fuNSACKd12*12')
      }
    }

  }
}