pipeline {
  agent none
  stages {
    stage('sahvsad') {
      steps {
        sh 'pipenv run sample'
      }
    }

    stage('fesdjkas') {
      steps {
        echo 'dsdsds'
        sh '''pipenv run sample
pipenv run sample
pipenv run sample'''
        sleep 5
      }
    }

    stage('sdfds') {
      steps {
        git(credentialsId: '0ea61500-b8fd-4e6a-b1c8-d4a3a1414224	', url: 'https://github.com/solveurits/pytestdemo.git', branch: 'main')
      }
    }

  }
}