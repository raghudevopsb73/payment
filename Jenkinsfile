pipeline {

  agent {
    node { label 'workstation'}
  }

  stages {

    stage('Unit tests') {
      steps {
        echo 'unit tests'
        //sh 'python -m unittest'
      }
    }

    stage('Code Analysis') {
      steps {
        echo 'Code Analysis'
      }
    }

    stage('Security Scans') {
      steps {
        echo 'Security Scans'
      }
    }

    stage('Publish a Artifact') {
      steps {
        echo 'Publish a Artifact'
      }
    }


  }

}