node {
  stage("Detect reference branch") {
    checkout scm
    discoverGitReferenceBuild defaultBranch: "main"
  }
}