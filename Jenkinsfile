pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Building!';
                sh 'mkdir bld && cd bld && cmake .. && make'
            }
        }

        stage('test') {
            steps {
                echo 'Testing!'
            }
        }


        stage('deploy') {
            steps {
                echo 'Deploying!'
            }
        }
    }
}
