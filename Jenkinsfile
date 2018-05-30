pipeline {
  agent any
  tools { docker 'docker'}
  stages {
    stage('Docker test') {
      steps {
        sh 'docker -v'
        tool(name: 'docker', type: 'docker')
      }
    }
  }
}
