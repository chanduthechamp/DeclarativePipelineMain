pipeline {
  agent any
  stages {
    stage ('Building 2 sub pipelines in parallel') {
      parallel {
        stage ('Build sub pipeline1') {
          steps {
            echo "Building Sub pipeline1"
            }
        }
        stage ('Build sub pipeline2') {
          steps {
            echo "Building Sub pipeline2"
          }
        }
      }
    }
  }
}
