pipeline {
  agent any
  stages {
    stage('Build and Test') {
      steps {
        git(url: 'https://github.com/jzajac2/echo-sonos', branch: 'master', changelog: true, credentialsId: ' 79f3be9f91ce08f77d819b213d9961036940dab9 ', poll: true)
      }
    }
  }
}