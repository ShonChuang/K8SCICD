pipeline {
   agent any

   stages {
      stage('單元測試') {
         steps {
           powershell label: '', script: 'dotnet test -v n'
         }
      }
   }
}
