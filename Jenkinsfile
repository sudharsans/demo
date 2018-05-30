pipeline {
  agent any
  tools { org.jenkinsci.plugins.docker.commons.tools.DockerTool 'docker'}
  stages {
    stage('Docker test') {
      steps {
        sh 'docker -v'
        tool(name: 'docker', type: 'docker')
      }
    }
  }
}
