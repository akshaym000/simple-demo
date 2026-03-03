pipeline{
  agent any

  stages{

    stage('clone'){
      git url:'https://github.com/akshaym000/jenkins-simple-demo.git',branch: 'main'
    }
  }
  stage('Run Script'){
    steps{
      sh 'chmod +x script.sh'
      sh './script.sh'
    }
  }
}
}
