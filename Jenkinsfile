pipeline{
	agent{ label 'aci-agent' }

	stages{
		stage('test .NET version'){
			steps {
				powershell 'dotnet --version'
			}
		}
	}
}