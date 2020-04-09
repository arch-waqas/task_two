// pipeline {
//     agent { docker { image 'php' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'php --version'
//             }
//         }
//     }
// }

pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'echo "Bismillah"'
                sh '''
                    echo "Multiline Command"
                    ls -alh
                '''
            }
        }
    }
}