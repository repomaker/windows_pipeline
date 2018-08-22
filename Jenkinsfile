pipeline{
	agent none

	stages{

		stage('test .NET version'){
			agent{
				docker { 
					image 'microsoft/dotnet:2.1-sdk-nanoserver-sac2016' 
					label 'windows-agent'
				}
			}
			steps {
				powershell 'dotnet --version'
			}
		}
	}
}