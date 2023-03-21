Pipelines{
    agent any

    stages{
        stage('Build Artificat')
        steps{
          sh "mvn clean package -DskipTests=true"
          archive 'target/* .jar'   
        }
    }
}
