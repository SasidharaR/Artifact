pipeline {
agent any
  stages {
    stage ('archive artifact') {
      steps {
        archiveArtifacts artifacts: 'test.txt', followSymlinks: false
      }
    }
  }
}
