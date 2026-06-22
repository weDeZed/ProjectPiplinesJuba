pipeline {
    agent any
    stages {
        stage('Intégration Continue (CI)') {
            steps {
                echo 'Étape CI : Récupération du code, compilation et exécution des tests...'
            }
        }
        stage('Déploiement Continu (CD)') {
            steps {
                echo 'Étape CD : Déploiement de la nouvelle version sur le serveur...'
            }
        }
    }
}
