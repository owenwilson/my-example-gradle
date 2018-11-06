pipeline {
agent any
	stages {
		stage ('GradleClean') {
			steps {
			echo 'gradle clean'
			sh 'gradle clean'
			}
		}
		stage ('GradleBuild') {
			steps {
			echo 'build gradle'
			sh 'gradle build'
			echo 'finished' 
			}
		}
		stage ('GradleUpload') {
			steps {
			echo 'Upload in progress'
			sh 'gradle upload'
			echo 'finished Up'
			}
		}
	}
}
