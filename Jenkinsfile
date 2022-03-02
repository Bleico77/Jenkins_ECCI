pipeline {
  agent {
    node {
      label 'Gaspar_HCM92'
    }

  }
  stages {
    stage('Consulta') {
      steps {
        sh 'psadmin -c sstatus -d ECHR92DV'
      }
    }

  }
}