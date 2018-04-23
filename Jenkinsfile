def branch_name = env.BRANCH_NAME != null ? env.BRANCH_NAME : 'master'

pipeline {
    agent any


    stages {
      stage('3_test_repo - tests') {
        steps {
          echo "We have run the tests against 3_test_repo"
        }
      }
      stage('3_test_repo - build') {
        steps {
          echo "We have built 3_test_repo"
        }
      }
    }
}
