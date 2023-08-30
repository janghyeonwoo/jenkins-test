pipeline {
  agent any
  parameters {
    gitParameter branchFilter: 'origin/(.*)',  name: 'BRANCH', type: 'PT_BRANCH'
  }
  stages {
    stage('Example') {
      steps {
        echo '$BRANCH'
        git branch: "${params.BRANCH}", url: 'https://github.com/janghyeonwoo/jenkins-test.git'
      }
    }
  }
}
