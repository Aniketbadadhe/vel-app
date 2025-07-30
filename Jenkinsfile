pipeline{
      agent{
		label{
			label 'built-in'
			customeWorkspace '/mnt/projects/vel-app/jenkins'
}
}

	stages{
		stage('install-appache'){
			steps{

			sh 'yum install httpd -y '

}


}

		stage('server-start'){
			steps{
				sh 'service httpd start'


}





}
		stage('index-deploy'){

			steps{
				sh 'cp -r index.html/var/www/html'
				sh 'chmod -R 777 /var/www/html/index.html
}
}


}
}
