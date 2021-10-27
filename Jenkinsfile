pipeline {
  agent any
  stages {
  stage("Compile") {
    steps {
      echo "Done Compiling" 
    }
  }
  stage("Running") {
    steps {
      sh "sample.py" 
    }
  }
  }
}
