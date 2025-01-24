pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo "Clone Repo."
            }
        }

        stage('Build') {
            steps {
                echo "Build App"
            
            }
        }

        stage('Save to Artifact') {
            steps {
                echo "Save Artifact to S3"

            }
        }
        stage('Downstream Pipeline to Deploy') {
            steps {
                echo "Trigger Deploy Pipeline"
                
            }
        }
    }

    post {
        always {
            echo "Notification"
        }
    }
}
