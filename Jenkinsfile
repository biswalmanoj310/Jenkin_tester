pipeline {
  agent any
  stages {
    stage('Prepare') {
      steps {
        echo "I am preperating"
      }
    }
    stage('Checkout') {
      steps {
        echo "I am checking out code"
      }
    }
    stage('TVP Checkout') {
      steps {
        echo "I am checking out tvp"
      }

      

    }
    stage('Checkout Status') {
      steps {
        echo "Checkout Status"
      }

    }
    stage('UI Build and Publish') {
      steps {
        echo "UI Build and Publish"
      }

    }
    stage('BUILDS') {
      steps {
        echo "I am checking out tvp"
      }

    }
    stage('Pub AFT and ULC and Evo Push') {
      steps {
        echo "I am checking out tvp"
      }

    }
    stage('Junos/TVP Pointer Update') {
      steps {
        echo "I am checking out tvp"
      }

    }
    stage('Parallel') {
      steps {
        echo "I am checking out tvp"
      }

    }
    stage('Junos/TVP Pointer Commit') {
      steps {
        echo "I am checking out tvp"
      }

    }
    stage('Image Copy') {
      steps {
        echo "I am checking out tvp"
      }

    }
    stage('CI Sanities') {
      steps {
        echo "I am checking out tvp"
      }

    }
    stage('Archive') {
      steps {
        echo "I am checking out tvp"
      }

    }
    stage('Final Status') {
      steps {
        echo "I am checking out tvp"
      }

    }

  }



  post {
    always{
      echo "Always say: Ram Ram Ram"
    }

    success {
      echo "----------------------"
      echo "ONLY on SUCCESS"
    }

    failure {
      echo "----------------------"
      echo "ONLY on failure"
    }


    unstable {
      echo "----------------------"
      echo "ONLY on unstable"
    }

    changed {
      echo "----------------------"
      echo "ONLY on status change"
    }

  }

}
