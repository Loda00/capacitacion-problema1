#!/usr/bin/env groovy

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "gg xd"
            }
        } 
    }
    parameters {
        choice(
            name: 'DEPLOY',
            choices: ["gh-page","aws"],
            description: "Ambiente de despliegue")
    }
}