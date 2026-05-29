pipeline {
    agent { label 'docker' } // This forces Jenkins to run the job on your isolated node!
    
    stages {
        stage('Initialize Build Environment') {
            steps {
                echo 'Securing pipeline workspace inside the isolated container...'
                sh 'uname -a' // Prints the system information of the worker container
            }
        }
        stage('Execute Mock Build Load') {
            steps {
                echo 'Distributing build workload successfully...'
                sh 'echo "Project execution completed on codealpha-node!"'
            }
        }
    }
}