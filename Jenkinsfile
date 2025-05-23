pipeline {
  agent any

  stages {

    stage('Build') {
      steps {
        echo 'Building the application...'
        echo 'Tool: Maven (or npm for Node.js apps)'
      }
    }

    stage('Unit and Integration Tests') {
      steps {
        echo 'Running unit and integration tests...'
        echo 'Tool: JUnit, Mocha, or Jest'
      }
    }

    stage('Code Analysis') {
      steps {
        echo 'Running static code analysis...'
        echo 'Tool: SonarCloud or ESLint'
      }
    }

    stage('Security Scan') {
      steps {
        echo 'Scanning for vulnerabilities...'
        echo 'Tool: npm audit or Snyk'
      }
    }

    stage('Deploy to Staging') {
      steps {
        echo 'Deploying to staging environment...'
        echo 'Tool: AWS CLI, Docker, or SCP'
      }
    }

    stage('Integration Tests on Staging') {
      steps {
        echo 'Running integration tests on staging...'
        echo 'Tool: Selenium or Postman CLI'
      }
    }

    stage('Deploy to Production') {
      steps {
        echo 'Deploying to production environment...'
        echo 'Tool: AWS CLI or Ansible'
      }
    }

  }
}