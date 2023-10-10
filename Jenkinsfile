pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        git(url: 'https://github.com/ingaramop/mvn_springboot_jpa_pgsql_template', branch: 'main')
      }
    }

    stage('') {
      steps {
        sh 'mvn clean'
      }
    }

  }
}