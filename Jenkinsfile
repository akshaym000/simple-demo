pipeline {
  agent any

  stages {

    stage('Clone') {
      steps {
        git url: 'https://github.com/akshaym000/simple-demo.git',
          branch: 'main'
      }
    }

    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
