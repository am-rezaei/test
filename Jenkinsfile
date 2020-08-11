node{
    stage('checkout'){
        git 'https://github.com/am-rezaei/test'
    }
    stage('compile'){
        def mvnHome = tool name: 'maven-3', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
    }
}