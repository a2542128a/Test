pipeline {
  agent {
    node {
      label 'WIn'
    }

  }
  stages {
    stage('LuaBytes') {
      steps {
        bat(script: 'D:\\FGame_Trunk_ProtoorBytes\\LuaScriptToLuaBytes.bat', encoding: 'UTF-8', returnStatus: true)
      }
    }

  }
}