pipeline{
    agent any

    stages{
        stage('Git Checkout'){

            Steps{
                script{
                    git branch: 'main', url: 'https://github.com/thabosolvyng/java_app.git'
                }
            }
        }
    }
}
