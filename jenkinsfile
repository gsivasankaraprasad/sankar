pipeline {
  agent any
  stages {
   stage ("build") {
    steps {
      echo "build is started "
      sh "mkdir firstdirectory && touch filename11"
}
}
  stage ("deploy"){
     steps {
   echo "deploy is started"
   sh "mkdir seconddirectory && touch filename12"
}
}

  stage ("monitoring") {
      steps {
    echo "monitoring is started"
    sh "touch filename13"
}
}

}
}
