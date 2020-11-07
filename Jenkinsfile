pipeline {
  agent {
    node {
      label 'WIn'
    }

  }
  stages {
    stage('LuaBytes') {
      steps {
        bat(script: 'LuaScriptToLuaBytes', encoding: 'UTF-8', returnStatus: true)
      }
    }

  }
}