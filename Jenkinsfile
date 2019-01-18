def code

node {
  stage('Checkout') {
    checkout scm
  }

  stage('Load') {
    code = load 'example.groovy'
    code.example1()
  }

  stage('Execute') {
    code.example2()
  }
}


