pipeline {
  agent any
  // parameters {
  //   gitParameter branchFilter: '.*', defaultValue: 'master', name: 'BRANCH', type: 'PT_BRANCH'
  // }
  stages {
    stage('Example') {
      steps {
        git branch: "${params.BRANCH}", url: 'https://github.com/jenkinsci/git-parameter-plugin.git'
        echo 'zzzz'
      }
    }
  }
}
