pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git(url: 'https://github.com/kechyy/SCA-Cloud-School-Application', branch: 'master')
      }
    }

    stage('Build') {
      steps {
        echo 'Building'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}