pipeline{
  agent any
  stages {
  stage('maven install') {
    steps {
       withMaven(globalMavenSettingsConfig: 'null', jdk: 'jdk_1.8', maven: 'Maven1', mavenSettingsConfig: 'null') {
        sh 'mvn clean install'
      }
    }
  }

}

}
