pipeline {
  agent {
    node {
      label 'WIn'
    }

  }
  stages {
    stage('') {
      steps {
        svn 'svn://192.168.1.250/fgame/trunk/client/FGameNew'
        bat(script: 'LuaScriptToLuaBytes.bat', encoding: 'UTF-8')
      }
    }

  }
}