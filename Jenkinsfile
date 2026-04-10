pipeline {
    agent any {
        stages{
          stage('git checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/sthita933/project01-maven.git'
            }
          }
        }
    }
}