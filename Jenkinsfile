
node {
  stage('scm checkout') {
	checkout([$class: 'GitSCM',
		branches: [[name: 'origin/dev']],
		extensions: [[$class: 'WipeWorkspace']],
		credentialsId: '6107d8e5-fe4e-43c2-ae69-8730c09edecb',
		userRemoteConfigs: [[url: 'https://github.com/wintoo/Docker_Project.git']]
		])	


//      echo "scm checkout"
//      git branch: 'dev', 
//      credentialsId: '6107d8e5-fe4e-43c2-ae69-8730c09edecb', 
//      url: 'https://github.com/wintoo/Docker_Project.git'
  }
  
  stage('build') {
      echo "build"
  }
  
  stage('test') {
      echo "test"
  }
  
  stage('deploy') {
      echo "deploy"
  }
    
}
