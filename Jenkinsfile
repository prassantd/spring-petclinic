node {
    stage('git clone') {
        git branch: 'main', url: 'https://github.com/prassantd/spring-petclinic.git'
    }
    stage('build') {
        sh 'mvn package'
    }
}
