pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo 'Hello GitHub from BlueOcean 1527'
      }
    }
    stage('Stage2') {
      steps {
        build '/Case2/Delivery_Deploy'
      }
    }
  }
}