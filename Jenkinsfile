node{
  stage("1")
  
  pipeline {
agent any
    stages {
        stage ('Run Python') {
            steps {
                    git branch: 'test', url: 'https://github.com/dddf1/desktopshit.git'
                    python3 hello.py
                 }
            }
    }
}
