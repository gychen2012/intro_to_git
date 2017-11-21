pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('write_to_file') {
      steps {
        echo 'Please provide VC and ESX build ${vc_build}. '
        sh 'echo "This is the first test'
      }
    }
  }
  environment {
    vc_build = 'this is the vc build'
    esxi_build = 'this is esxi build'
  }
}