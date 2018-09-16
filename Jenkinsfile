#!/usr/bin/env groovy

@Library('ZomisJenkins')
import net.zomis.jenkins.Duga

pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }

        stage('Deploy') {
            when {
                branch 'master'
            }
            steps {
                dir('dist') {
                    sh 'git init'
                    sh 'git add -A'
                    sh 'git commit -m"deploy"'
                    sh 'git push -f git@github.com:Zomis/zomis.github.io.git master'
                }
            }
        }
    }

    post {
        success {
            zpost(0)
        }
        unstable {
            zpost(1)
        }
        failure {
            zpost(2)
        }
    }
}
