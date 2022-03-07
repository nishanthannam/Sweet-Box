pipeline
{
	agent any
	
		stages
		{
			stage('Building a Command')
			{
					steps
				{
				echo 'Hello Build to the World'
				}
			}
			
			stage('Testing a Command')
			{
				steps
				{
				echo 'Hello Test to the World'
					sh '''
						cat Read.bash
					'''
				}
			}
			
			stage('Deploying a Command')
			{
				steps
				{
				echo 'Hello Deploy to the World'
				}
			}
		}
}
