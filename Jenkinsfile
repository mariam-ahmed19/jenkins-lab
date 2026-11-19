pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                bat '"C:\\tools\\jdk\\jdk-21.0.13.9-hotspot\\bin\\javac.exe" HelloWorld.java'
            }
        }

        stage('Run') {
            steps {
                bat '"C:\\tools\\jdk\\jdk-21.0.13.9-hotspot\\bin\\java.exe" HelloWorld'
            }
        }
    }
}
