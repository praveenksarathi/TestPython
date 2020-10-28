node {
  stage ("checkout") {
    checkout scm
  }
  stage ("Build") {
    sh "ls -lrt"
//  sh "python3 app/app/python.py"
  }
  
  stage ("Commit") {
  sleep 5
  echo "The commit stage has passed"
  }
  
  stage ("Deploy") {
  sleep 4
  echo "The Deploy stage has passed"
  }
}
