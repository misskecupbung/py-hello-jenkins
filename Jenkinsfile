node {
    stage('Checkout') {
        checkout scm
    }

    stage('Build') {
        sh "python3 hello.py"
    }
}
