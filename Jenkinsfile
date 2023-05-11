pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is Build stage'
            }
        }
         stage('Test')
{
steps{
echo " this is test stage"


}
}

stage("deploy")
{
steps{
echo " this is deploy stage"

}

}

}
post{

always
{

emailext body: 'Here is the status of project ', subject: 'Project Details', to: 'rekha580.shankar@gmail.com'
}
}


		 
	    
}
