pipeline {
 agent {
    node {
      label 'master'
      customWorkspace 'd:/jenkinTest'
    }
  }
  stages {
    stage('') {
      steps {
        node(label: 'master') {
          ws(dir: 'd:/jenkinTest')
        }

      }
    }
  }
}
