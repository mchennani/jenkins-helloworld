node {
    stage('clone') {
        git 'https://github.com/mchennani/jenkins-helloword'
}
stage('build') {
    sh label: '', script: 'javac Main.java'
}
stage('run') {
    sh label: '', script: 'java Main'
}
    
}
