node {
  checkout scm
  
  // Build
  stage 'Build'
  sh("cd complete; mvn package;")
  
  // Run tests
  stage 'Run tests'
  sh("echo Run test")

  // Publish
  stage 'Publish image to registry'
  sh("echo Publish image")
}
