pipeline {
  agent any
  stages {
    stage('Git') {
      steps {
        git(url: 'https://github.com/SaiSriHarsha333/Software_project.git', branch: 'master')
      }
    }
    stage('Change Dir') {
      steps {
        dir(path: '/rms/')
      }
    }
  }
}