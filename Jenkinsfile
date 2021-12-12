pipeline {
    agent any

    stages {
       steps {
          echo "SCM checkout"
       }
    }

    stages {
       steps {
          echo "build"
       }
    }
    stages {
       steps {
          echo "build war file"
       }
    }
    stages {
       steps {
          echo "test"
       }
    }
    stages {
       steps {
          echo "upload artifact to nexus"
       }
    }
    stages {
       steps {
          echo "build"
       }
    }
}
