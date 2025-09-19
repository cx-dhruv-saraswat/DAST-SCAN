// /* Requires the Docker Pipeline plugin */
// pipeline {
//     agent { docker { image 'maven:3.9.11-eclipse-temurin-21-alpine' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'mvn --version'
//             }
//         }
//     }
// }

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
