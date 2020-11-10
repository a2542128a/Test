pipeline {
  agent {
    node {
      label 'WIn'
    }

  }
  stages {
    stage('LuaBytes') {
      steps {
        bat(script: 'cd D:\\FGame_Trunk_ProtoorBytes svn up', returnStatus: true)
        bat(script: 'cd D:\\FGame_Trunk_ProtoorBytes LuaScriptToLuaBytes.bat', encoding: 'UTF-8', returnStatus: true)
      }
    }

  }
}