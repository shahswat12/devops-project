pipeline{

    agent any

    stages{

        stage('git checkout'){

            steps{

                script{

                    git branch: 'main', url: 'https://github.com/shahswat12/devops-project.git'
                }
            }
        }
    }
}