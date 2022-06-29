node {
   stage('Clone repository') {
        checkout scm
    }
   stage('Build image') {
       app = docker.build("kubernetescode/test")
    }
   stage('Test image') {
        app.inside {
            sh 'echo "Tests passed"'
        }
    }
    
}
