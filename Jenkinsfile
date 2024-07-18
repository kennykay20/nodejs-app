pipeline { // pipeline must be top-level

  agent any  // agent - where to execute

  stages { // stages - where the 'work' happens
    stage("build") {
      steps {
        // inside here we have the scripts that execute some commands on the jenkins server
        echo 'building the application'
      }
    }

    stage("test") {
      steps {
        echo 'testing the application'
      }
    }

    stage("deploy") {
      steps {
        echo 'deploying the application'
      }
    }
  }
}
