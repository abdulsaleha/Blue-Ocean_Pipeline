pipeline {
  agent any
  stages {
    stage('Dev Stage') {
      parallel {
        stage('Dev') {
          steps {
            echo 'Developing Stage'
          }
        }

        stage('2nd Dev') {
          steps {
            echo '2nd Dev'
          }
        }

        stage('3rd Dev') {
          steps {
            echo '3rd'
          }
        }

      }
    }

    stage('Testing Stage') {
      steps {
        echo 'Testing Team'
      }
    }

    stage('Q&A stage') {
      steps {
        echo 'Q&A team'
      }
    }

    stage('UTS Stage') {
      steps {
        echo 'UTS team'
      }
    }

    stage('Production Stage') {
      steps {
        echo 'Pro Stage'
      }
    }

  }
}