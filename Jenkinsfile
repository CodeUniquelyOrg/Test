pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        git(url: 'https://github.com/CodeUniquelyOrg/test.git', branch: 'master', changelog: true)
      }
    }

  }
}