pipeline {
  agent any
  stages {
    stage('Docker test') {
      steps {
        tool(name: 'docker', type: 'org.jenkinsci.plugins.docker.commons.tools.DockerTool')
        sh 'docker -v'
      }
    }
  }
}