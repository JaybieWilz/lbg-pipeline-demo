pipeline{

        agent any

        stages{

            stage('Make Directory'){

                steps{

                    sh "mkdir ~/jenkins-tutorial-test"

                }

            }

            stage('Execute Shell'){

                steps{

                    sh "echo ~/Hello from the Jenkins job"

                }

            }

            stage('Create Files'){

                steps{

                    sh "touch ~/ 1.txt 2.txt 3.txt 4.txt 5.txt"

                }

            }

            stage('Zip and Archive'){

                steps{

                    sh "zip ~/ archive.zip *.txt"

                }
            }

        }
}