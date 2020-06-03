node{
 stage('SCM Checkout'){
git 'https://github.com/Autamation/sim.git'
}
stage('Compile-Package'){
   def mvnHome = tool name: 'maven3', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
 sh 'mvn package'
}
}
