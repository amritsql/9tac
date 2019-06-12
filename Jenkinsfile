pipeline {
  agent any
    
 // tools {nodejs "node"}
    
  stages {
        
    stage('Cloning Git') {
      steps {
        git 'https://github.com/gustavoapolinario/node-todo-frontend'
      }
    }
        
    stage('SAST') {
      steps {
        echo '#### sast scan started #########'
        echo '#### sast scan end #############'
      }
    }
     
    stage('Build-and-Tag') {
      steps {
         echo 'build & tagging completed'
      }
    }  
     stage('post-to-dockerhub') {
      steps {
         echo 'successfully posted to dockerhub'
      }
    }  
    stage('pull-image-server') {
      steps {
         echo 'successfully posted to dockerhub'
      }
    }  
    stage('DAST') {
      steps {
         echo 'successfully posted to dockerhub'
      }
    }  
    
  }
}
