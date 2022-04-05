@Library('SLDemo') _

pipeline{
    agent any
    stages{
        stage(demo){
            steps{
                helo("Naveen")
                script{
                    cal.add(5,6)
                    cal.mul(2,4)
                }
            }
        }
    }
}