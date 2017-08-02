node {
    stage('repository_pull') {
     sh 'hostname'
	 sh 'echo ${env:DEPLOYMENT-RELEASE}'
    }
    
    stage("composer_install") {
      sh 'echo 123456'
    }

    stage('cleanup-everything') {
	  sh 'ifconfig'
    }
}