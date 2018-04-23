def branch_name = env.BRANCH_NAME != null ? env.BRANCH_NAME : 'master'

pipeline {
    agent any


    stages {
      stage('vmbuild tests') {
        steps {
          echo "We have run the tests against vmbuild"
        }
      }
      stage('vmbuild build') {
        steps {
          echo "We have built vmbuild"
        }
      }
    }
}
