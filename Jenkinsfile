pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'sh \'mvn -Dtest=${TEST} test --batch-mode -Dmatsim.preferLocalDtds=true -Dmaven.javadoc.skip -e\''
      }
    }

  }
}