node
{
    def mavenHome = tool name: 'maven', type: 'maven'

    stage("contdonwload")
    {
        git branch: 'rishabh', url: 'https://github.com/expertisedevops/DevOpsMultibranch.git'
    }
    stage("contbuild")
    {
        sh "'${mavenHome}/bin/mvn'  package"
    }
    stage("cont-deploy")
    {
        sh "echo hello world"
        sleep 20
    }
    stage("cont_test")
    {
        sleep 20
    }
}
