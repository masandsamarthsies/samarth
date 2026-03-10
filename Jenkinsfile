pipeline{
  agent any
  stages{
    stage('checkout'){
      step{
        echo 'checking out Repo'
        git 'https://github.com/masandsamarthsies/samarth.git'
}
}
stage('Publish'){
  steps{
    publishHTML([
      allowMissing:true,
      alwaysLinkToLastBuild:false,
      keepAll:false,
      reportDir:'.',
      reportFiles:'index.html',
      reportName:'MY HTML PIPE PAGE'
      ])
      
}
}
  
}
