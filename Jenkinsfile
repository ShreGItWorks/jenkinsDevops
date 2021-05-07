pipeline{
	agent any
	stages{
		stage('checkout'){
			steps{
				checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'd4d32a6b-e783-42fe-a71c-f6292fa01e65', url: 'https://github.com/ShreGItWorks/jenkinsDevops.git']]])
			}
		}
		stage('Build'){
			steps{
				echo "Hello"
			}
			
		}
	}

}