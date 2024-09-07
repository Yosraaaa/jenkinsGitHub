
pipeline {
  
          agent any

          stages{
            stage('Get from git project'){
  steps {
    git 'https://github.com/MezghichGit/mavenJunitProject'
  }
            }

           // Create a new .jar file 

            stage('Create a new .jar') {

                steps {
                    
                   bat 'mvn clean install -DskipTests'
                   echo "Success"
                
                      }

          
            }
}
}
