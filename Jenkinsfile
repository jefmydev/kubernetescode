node {
   stage('Clone repository') {
        checkout scm
    }
   stage('Build image') {
       app = docker.build("kubernetescode/test")
    }
    
}
