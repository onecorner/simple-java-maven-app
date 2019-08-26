node {
    checkout scm
    stage('Build') {
        sh 'echo "Hello World"'
        sh '''
            pwd
            echo "Multiline shell steps works too"
            ls -lah
           '''
    }
    stage('Test') {
        echo 'Building....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}