pipeline {
  agent none
  stages {
    stage('write_to_file') {
      steps {
        writeFile(file: 'test', text: 'abcdefg', encoding: 'UTF-8')
      }
    }
  }
  environment {
    vc_build = ''
    esxi_build = ''
  }
}