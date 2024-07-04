pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build stage'
      }
    }

    stage('Test') {
      steps {
        echo 'testing complete'
      }
    }

    stage('Deploy to staging') {
      steps {
        writeFile(file: '\'test-file.txt\'', text: '\'This is an example content.\'')
      }
    }

  }
}