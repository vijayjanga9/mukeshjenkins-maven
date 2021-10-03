pipeline 
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
           
                echo 'Deploy App'
            }
        }
    }

    post
    {

    	always
    	{
    		emailext body: 'Summary', subject: 'Pipeline Status', to: 'vijaydocs100@gmail.com'
    	}

    }
}
