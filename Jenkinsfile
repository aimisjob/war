node{
  stage('git checkout'){
    git 'https://github.com/aimisjob/war'
}
 stage('package'){
   tool name: 'mvn', type: 'maven'
   sh 'mvn package'
  }
}

  
