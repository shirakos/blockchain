pipeline{
agent any
tools{
        maven 'MAVEN_HOME'
        jdk 'JAVA_HOME'
}
stages{
      stage('Compilation du projet')
      {
        steps{
           bat 'mvn compile'
              }
      }
}

}
