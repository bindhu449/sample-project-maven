pipeline{
   agent any
   tools {
      maven 'maven'
      jdk 'JAVA_HOME'
   }
   stages {
    stage ('build')
      {
      steps {
      echo "building a maven project"
         sh 'mvn compile'
      }

}  
 stage ('test')
      {
      steps {
      echo "testing"
         sh 'mvn test'
      }

}  


}

}
