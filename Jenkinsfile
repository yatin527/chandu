node('New') {
    stage('GIT') {
    git 'https://github.com/yatin527/chandu.git'
}
    stage('PACK') {
    sh label: '', script: 'mvn package'
}
}
