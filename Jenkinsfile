pipeline {
	agent any

	stages {
		stage('Checkout') {
			steps {
				echo "This is git clone stage"
<<<<<<< HEAD
=======
				sh "pwd"
>>>>>>> refs/remotes/origin/main
				sh "sleep 5"
				sh "ls -lrt"
			}
		}

		stage('Build') {
			steps {
				sh ''' 
					echo Complie and build the package
<<<<<<< HEAD
=======
					pwd
>>>>>>> refs/remotes/origin/main
				    sleep 5
				'''
			}
		}

		stage('Test') {
			steps {
				sh """
					#!/bin/bash
					echo This is Integration testing
<<<<<<< HEAD
=======
					pwd
>>>>>>> refs/remotes/origin/main
					sleep 5
					ls -lrt
				"""
			}
		}
	}
}
