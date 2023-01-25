pipeline{
 agent{
    label 'ansible'
 }
 stages('Hello') {
   steps {
     echo 'Hello World'
   }
 }

  stages('Hello another stages') {
    steps {
      echo 'Hello from another stages'
    }
  }

}