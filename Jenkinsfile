
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'echo 'Hello depuis GitHub - Modification 2'
            }
        }

        stage('Infos environnement') {
            steps {
                echo "Nom du noeud Jenkins: ${env.NODE_NAME}"
                echo "Workspace: ${env.WORKSPACE}"
            }
        }
    }
}
