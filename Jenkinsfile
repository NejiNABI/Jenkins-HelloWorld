node {
    stage('Clone') {
        git 'https://github.com/NejiNABI/Jenkins-HelloWorld.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}
