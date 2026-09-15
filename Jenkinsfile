pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Task: Compile and package the source code.'
                echo 'Tool: Apache Maven.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Task: Run unit tests and test how different components work together.'
                echo 'Tools: JUnit for unit testing and Selenium for integration testing.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Task: Analyse the source code for bugs, maintainability issues and coding-standard violations.'
                echo 'Tool: SonarQube.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Task: Scan the application and its dependencies for known security vulnerabilities.'
                echo 'Tool: OWASP Dependency-Check.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Task: Deploy the application to a staging server for pre-production testing.'
                echo 'Tools: AWS EC2 and AWS CodeDeploy.'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Task: Run integration tests in the staging environment to confirm the application works correctly.'
                echo 'Tool: Postman with Newman.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Task: Deploy the approved application to the production server.'
                echo 'Tools: AWS EC2 and AWS CodeDeploy.'
            }
        }
    }
}