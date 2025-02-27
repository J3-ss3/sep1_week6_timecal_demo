pipeline {
  agent any
  stages {
    stage ('checking'){
      steps {
        git branch: 'mail', url: 'https://github.com/J3-ss3/sep1_week6_timecal_demo.git'
      }
    }

    stage (build) {
      steps{
        sh 'mvn clean install'
      }
    }
  }
}
