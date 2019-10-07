#!/usr/bin/groovy
pipeline {
	agent any

	stages {

		stage('Build') {
			steps {
				sh '''
				echo 'Building..'
				mvn --version
				mvn build
				'''
			}
		}

		stage('Test') {
			steps {
				echo 'Testing..'
			}
		}

		stage('Deploy') {
			steps {
				echo 'Deploying....'
			}
		}

	}
}
