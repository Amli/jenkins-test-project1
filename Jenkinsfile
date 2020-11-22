node {
  stage('build') {
    def scmInfo = checkout(scm)
    echo "${scmInfo}"
    echo sh(script: 'env|sort', returnStdout: true)
    echo "Hello world"
  }
}
