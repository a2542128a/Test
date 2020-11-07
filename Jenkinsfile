pipeline {
  agent {
    node {
      label 'WIn'
    }

  }
  stages {
    stage('error') {
      steps {
        svn 'svn://192.168.1.250/fgame/trunk/client/FGameNew'
      }
    }

    stage('LuaBytes') {
      steps {
        bat(script: 'LuaScriptToLuaBytes', encoding: 'UTF-8', returnStatus: true)
      }
    }

  }
}