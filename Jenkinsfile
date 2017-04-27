node {
  checkout scm
  
  // Build
  stage 'Build'
  sh("cd complete; mvn package;")
  
  // Run tests
  stage 'Test'
  sh("echo Run test")

  // Publish
  stage 'Publish docker image'
  sh("echo Publish image")
}
