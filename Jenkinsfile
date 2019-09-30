node{
 stage('SCM Checkout'){
git 'https://github.com/Autamation/sim.git'
}
stage('Compile-Package'){
   def mvnHome = tool name: 'M2-HONE', type: 'maven'
      bat "${mvnHome}/bin/mvn package"
 bat 'mvn package'
}
}
