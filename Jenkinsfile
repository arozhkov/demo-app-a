node {
    stage('Init') {
        echo '=== Init'
        
    }
    stage('Build') {
        echo '=== Build'
        sh '/kaniko/executor --destination=189141687483.dkr.ecr.us-east-1.amazonaws.com/arozhkov/demo-app-a:1.0.7 -v info'
    }
    stage('Report') {
        try {
            echo '=== Report'
            sh 'ls'
        } catch(Exception e) {
            echo 'Catch an exception'
        }
    }
}
