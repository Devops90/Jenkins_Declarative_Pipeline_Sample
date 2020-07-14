# Jenkins_Pipeline_Sample

Declarative pipeline syntax:-
===========================
pipeline {
    agent any
    stages {
        stage('print message') {
            steps {
                echo 'Welcome Hari'
            }
        }
    }
}


