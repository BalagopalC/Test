pipeline {
 agent {
    node {
      label 'master'
      customWorkspace 'd:d:/jenkinTest'
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
