node{
   stage("Checkout SCM"){

     

    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'github', url: 'https://github.com/mahadevops12/Java-webapp.git']]])

  }
stage("Build"){
sh "mvn package"
}
}
