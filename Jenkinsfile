pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        git(url: 'https://github.com/dward2nd/fblogin-mockup', branch: 'main')
        sh 'npx http-server .'
      }
    }

  }
}