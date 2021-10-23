pipeline{
 agent any
   stages {
    stage ('gitclone') {
     steps {
         sh "ls -lrt"
         sh "rm -rf sankar"
         echo "gitclone is started"
         sh "git clone https://github.com/gsivasankaraprasad/sankar.git"
         sh "ls -lrt"
}
}
     stage('maven') {
        steps {
        echo "maven build is started"
         sh "mvn clean install"

}
}
   }
}
