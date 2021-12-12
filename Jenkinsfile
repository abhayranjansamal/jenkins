pipeline {
    agent any

    stage {
       steps {
          echo "SCM checkout"
       }
    }

    stage {
       steps {
          echo "build"
       }
    }
    stage {
       steps {
          echo "build war file"
       }
    }
    stage {
       steps {
          echo "test"
       }
    }
    stage {
       steps {
          echo "upload artifact to nexus"
       }
    }
    stage {
       steps {
          echo "build"
       }
    }
}
