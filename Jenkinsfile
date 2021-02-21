pipeline {
  agent any
  stages {
    stage('SCM') {
      steps {
        git(url: 'https://github.com/rishabhsikka/maven-myapp.git', branch: 'feature2')
      }
    }

    stage('build') {
      steps {
        sh 'mvn clean install'
      }
    }

  }
}