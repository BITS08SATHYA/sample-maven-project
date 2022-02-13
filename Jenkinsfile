pipeline{
  agent any
  stages {
  stage('maven install') {
    steps {
       withMaven(globalMavenSettingsConfig: 'f63af11d-bef1-475a-acc9-23e34a878a4c', jdk: 'jdk_1.8', maven: 'Maven1', mavenSettingsConfig: '9af61e4c-ac8d-4512-86b1-8ce2e330bc1f') {
        sh 'mvn clean install'
      }
    }
  }

}

}
