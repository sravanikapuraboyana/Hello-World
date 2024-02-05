pipeline {
  agent any
  stages {
    stage('buld') {
      steps {
        echo 'i want to build'
      }
    }

    stage('test') {
      steps {
        echo 'build tested'
      }
    }

    stage('deploy') {
      steps {
        git(url: 'https://github.com/sravanikapuraboyana/Hello-World.git', branch: 'master', changelog: true, poll: true)
      }
    }

  }
}