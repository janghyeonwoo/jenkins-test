pipeline {
    agent any
    parameters {
    gitParameter branchFilter: 'origin/(.*)', defaultValue: 'master', name: 'BR_NAME', type: 'PT_BRANCH'
  }
  stages {
    stage('Example') {
      steps {
        git branch: "${params.BR_NAME}", url: 'https://github.com/janghyeonwoo/jenkins-test.git'
      }
    }
  }

}
