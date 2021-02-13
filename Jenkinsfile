node{
	stage('SCM Checkout'){
		git 'https://github.com/moganraj/HelloWorld'
	}
	stage('Compile-Package'){
		sh 'mvn package'
	}
}