node {
  stage('Example') {
    checkout scm
    withGradle {
      sh 'gradle wrapper'
    sh './gradlew build'
    }
  }
}
