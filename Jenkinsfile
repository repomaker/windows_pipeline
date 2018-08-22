pipeline{
	agent{
		docker { 
			image 'microsoft/dotnet:2.1-sdk-nanoserver-sac2016' 
			label 'windows-agent'
		}
	}

	stages{

		stage('test .NET version'){
			
			steps {
				powershell 'dotnet --version'
			}
		}
	}
}