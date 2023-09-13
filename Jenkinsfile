pipeline {
  agent any
  parameters {
    gitParameter branchFilter: 'origin/(.*)', defaultValue: 'master', name: 'BRANCH', type: 'PT_BRANCH'
  }
  stages {
    stage('Example') asaaasas
      steps {
        echo '$BRANCH'
        git branch: "${params.BRANCH}", url: 'https://github.com/janghyeonwoo/jenkins-test.git'
      }
    }
  }
}
SDF
