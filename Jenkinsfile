pipeline {
    agent any
    parameters {
        string(name: 'company_parameter', defaultValue: 'puzzle', description: 'The company the pipeline runs in')
    }
    stages {
        stage('Build') {
            steps {
                echo "Running g ${env.BUILD_ID} on ${env.JENKINS_URL} in company ${params.company_parameter}"
            }
        }
    }
}
