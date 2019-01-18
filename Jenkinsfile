def code

node {
  stage('Checkout') {
    checkout scm
  }

  stage('Load') {
    code = load 'example.groovy'
    code.example1()
    code.example2()
  }

  stage('Execute') {
    code = load 'example2.groovy'
    code.example3()
    code.example4()
    
  }
}


