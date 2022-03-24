pipeline {
    agent none
    stages {
        
      stage('run-parallel-branches') {
  steps {
    parallel(
      a: {
        echo "This is branch 1"
      },
      b: {
        echo "This is branch 2"
      }
    )
  }
}
}
}
