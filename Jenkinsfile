node {
    stage('Init') {
        echo '=== Init'
        
    }
    stage('Build') {
        echo '=== Build'
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
