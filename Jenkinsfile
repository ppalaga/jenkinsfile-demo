parallel (
    a : {
        node('maven') {
            stage('Test Linux') {
                echo 'Building...'
            }
        }
    },
    b : {
        node('maven') {
            stage('Test Windows') {
                echo 'Building...'
            }
        }
    }
)
