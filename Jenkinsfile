pipeline {
  environment {
    CC = """${sh(
                returnStdout: true,
                script: 'echo "clang"'
        )}""" 
    EXIT_STATUS = """${sh(
            returnStatus: true,
            script: 'exit 1'
        )}"""
  }
  agent any
  stages {
    stage('hello'){
      steps {
        sh "printenv"
      }
    }
  }
}
