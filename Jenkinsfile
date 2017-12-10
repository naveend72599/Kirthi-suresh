node {
    stage('cloning the project'){
        echo 'Hello World'
        git 'https://github.com/naveend72599/Kirthi-suresh.git'
    }
    stage('Deploy artifacts'){
       archiveArtifacts 'target/*.jar'
    }
   stage('compile and packaging and unit testing'){
       echo 'compling source code and '
       sh 'mvn clean compile package'
   }
   stage('Unit testing'){
       echo 'testing the changes'
   }
   stage('Dev'){
       
   }
   stage('Production stage'){
       echo 'deploying the changes in production'
   }
}
