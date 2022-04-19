node {
  stage('Example') {
    checkout scm
    withGradle('Gradle7.2') {
    sh './gradlew build'
    }
  }
}
