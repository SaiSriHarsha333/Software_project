pipeline {
  agent any
  stages {
    stage('Git') {
      steps {
        git(url: 'https://github.com/SaiSriHarsha333/Software_project.git', branch: 'master')
      }
    }
    stage('Change repo') {
      steps {
        git(url: 'https://github.com/SaiSriHarsha333/Software_project/tree/master/rms', branch: 'master')
      }
    }
  }
}