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
                sh 'echo "Bismillah"'
                sh 'html_lint.py index.html'
            }
        }
    }
}