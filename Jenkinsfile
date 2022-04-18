@Library('pipeline-shared-demo') _

pipeline{
    agent any
    stages{
        stage('Demo'){
            steps {
                welcome("Irfan Rizkianto Pratama")
                script{
                    calculator.add(10,20)
                    calculator.multiply(10,20)
                }
            }
        }
    }
}