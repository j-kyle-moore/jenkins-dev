pipeline {
  agent any
  stages {
    stage('Copy config files') {
      steps {
        sh 'kubectl cp jcasc-default-config.yaml jenkins/jenkins-commercial-0:/var/jenkins_home/casc_configs/jcasc-default-config.yaml'
      }
    }

  }
}