pipeline {
    agent any
    environment{
        user = 'divya'
        password = 'div123'
    }

    stages {
        stage("info") {
            steps {
                echo "name is $user"
                echo "password is $password"
            }
        }
    }
}
