pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Etape de build"
				sh 'python3 --version'
                python3 dateEnPython.py
			}
		}
		stage('Tests') {
			steps { 
				echo "Etape de test"
			}
		}
		stage ('Deploy') {
			steps {
				echo "Etape de déploiement"
			}
		}
	}
}
