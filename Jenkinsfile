pipeline{
 agent any
   stages {
    stage ('gitclone') {
     steps {

         echo "gitclone is started"
         sh "git clone https://github.com/gsivasankaraprasad/sankar.git"
         sh "ls -lrt"
}
}
     stage('build') {
        stpes {
        echo "maven build is started"
         echo "mvn clean install"

}
}
   }
}
