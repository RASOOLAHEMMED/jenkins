pipeline {

//     agent {
//             //node { label 'workstation' }
//             //label 'JAVA'
//             none
//            }


    agent none

    stages {

        stage('Master Node') {
            agent {
                label 'MASTER'
            }
             steps {
                sh 'echo Hello'
                }
            }
            stage('Agent Node') {
                agent {
                    label 'JAVA'
                }
                steps {
                    sh 'echo Hello'
                }
            }

        }

                    post {
                        agen any

                        always {
                            sh 'echo post steps'
                        }
                    }
}