pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'git@github.com:eestor/spring-boot-samples.git', branch: 'master', credentialsId: '67e98dce41f53957ab61dc86c6b22f23c5e9a4c5')
      }
    }
  }
}