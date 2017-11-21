pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('write_to_file') {
      steps {
        writeFile(file: 'test', text: 'abcdefg', encoding: 'UTF-8')
        pwd()
      }
    }
  }
  environment {
    vc_build = ''
    esxi_build = ''
  }
}