pipeline {
    agent any

    stages {
        stage('terraform init') {
            steps {
              sh 'terraform init'
            }
        }
        stage('terraform validate') {
            steps {
               sh 'terraform validate'
            }
        }
        stage('teraform plan') {
            steps {
               sh 'terraform plan'
            }
        }
        stage('terraform apply') {
            steps {
               sh 'terraform apply --auto-approve'
            }
        }
    }
