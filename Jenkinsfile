pipeline {
    agent none
    stages {
        
      stage('run-parallel-branches') {
  steps {
    parallel(
      a: {
        echo "This is branch x"
      },
        steps {
      b: {
        echo "This is branch y"
      }
        }
    )
  }
}
}
}
