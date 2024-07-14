pipeline {
	agent any

	stages {
		stage('Checkout') {
			steps {
				echo "This is git clone stage"
				sh "pwd"
				sh "sleep 5"
				sh "ls -lrt"
			}
		}

		stage('Build') {
			steps {
				sh ''' 
					echo Complie and build the package
					pwd
				    sleep 5
				'''
			}
		}

		stage('Test') {
			steps {
				sh """
					#!/bin/bash
					echo This is Integration testing
					pwd
					sleep 5
					ls -lrt
				"""
			}
		}
	}
}
