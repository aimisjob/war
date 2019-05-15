node{
  stage('git checkout'){
    git 'https://github.com/aimisjob/war'
}
 stage('package'){
   def mavenhome=tool name: 'mvn', type: 'maven'
   sh "${mavenhome}/bin/mvn package"
  }
}

  
