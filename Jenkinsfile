pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        dockerNode(image: 'python:3.7.4-slim') {
          sh '''sh \'echo "Hello 

sh \'\'\'
echo "Multiline shell steps works too"
ls -lah
\'\'\''''
        }

      }
    }
  }
}