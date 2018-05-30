pipeline {
  agent any
  stages {
    stage('Docker test') {
      steps {
        sh 'docker -v'
        tool(name: 'docker', type: 'org.jenkinsci.plugins.docker.commons.tools.DockerTool')
      }
    }
  }
}