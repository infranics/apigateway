pipeline {
  agent {
    node {
      label 'apigateway2'
    }

  }
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/infranics/apigateway.git', branch: 'main', poll: true, credentialsId: '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')
      }
    }

  }
}