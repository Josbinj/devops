Pipeline{
    agent any 
    stages{
        stage('git checkout'){
            steps{
                script{
                    git branch: 'main', url: 'https://github.com/Josbinj/devops.git'
                }
            }
        }
    }

}