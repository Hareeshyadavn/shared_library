@library("shared_library") _
pipeline{
  agent any
  stages{
    stage ('hello'){
      steps {
        sh ''' ls '''
        echo "hello man"
        helloworld()
      }
    }
  }
}
