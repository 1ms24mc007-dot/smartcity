pipeline
{
	agent any
	stages
	{
		stage('Checkout')
		{
			steps{
				git branch: 'main',url: 'https://github.com/1ms24mc007-dot/my_first_pro'
			}
		}
		
		stage('Build')
		{
			steps
			{
				echo "Building..."
			}
		}
		stage('Test')
		{
			steps
			{
				echo "Testing..."
			}
		}
	}
}
