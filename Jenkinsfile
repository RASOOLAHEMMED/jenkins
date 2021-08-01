// pipeline {
//
// //     agent {
// //             //node { label 'workstation' }
// //             //label 'JAVA'
// //             none
// //            }
//
//
//     agent any
//
//     stages {
//
//         stage('Master Node') {
//             agent {
//                 label 'MASTER'
//             }
//              steps {
//                 sh 'echo Hello'
//                 }
//             }
//             stage('Agent Node') {
//                 agent {
//                     label 'JAVA'
//                 }
//                 steps {
//                     sh 'echo Hello'
//                 }
//             }
//
//         }
//
//                     post {
//                       always {
//                             sh 'echo post steps'
//                         }
//                     }
// }


pipeline {
    agent any

    environment {
        DEMO_URL = "google.com"
    }

    stages {
        stage('One') {
            steps {
            sh 'echo $(DEMO_URL)'
            }
        }
    }
}