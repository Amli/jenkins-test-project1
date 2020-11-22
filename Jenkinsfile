node {
  stage('build') {
    def scmInfo = checkout(scm)
    echo "${scmInfo}"
    echo sh(script: 'env|sort', returnStdout: true)
    if (env.CHANGE_ID) {
      plrintln pullRequest.dump()
    }
    echo "Hello world"
  }
}
