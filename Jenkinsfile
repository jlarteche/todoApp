pipeline {
  agent { label 'nodo-principal' }
  // es lo mismo que agent { node { label 'nodo-principal' } } y que node{'nodo-principal'}
  //pero con node se permiten parametros como customWorkspace '/some/other/path' pasado igual que label.
  stages {
    stage('1') {
      steps {
        echo 'hola hola caracola'
      }
    }

  }
}