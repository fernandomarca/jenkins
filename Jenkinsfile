pipeline {
  agent {
    node {
      label 'test'
    }

  }
  stages {
    stage('git checkout') {
      steps {
        git(url: 'https://github.com/fernandomarca/jenkins.git', branch: 'master')
      }
    }

  }
}