pipeline {
  agent {
    node {
      label 'WIn'
    }

  }
  stages {
    stage('LuaBytes') {
      steps {
        bat(script: 'cd D:\\FGame_Trunk_ProtoorBytes', returnStatus: true)
        bat(script: ' svn up', returnStatus: true)
        bat(script: 'LuaScriptToLuaBytes.bat', encoding: 'UTF-8', returnStatus: true)
      }
    }

  }
}