node{
/*Comment*/
//Single line Comment
//https://youtu.be/pts8zdHel5E
	stage('SCM Checkout'){
		tool name: 'apache-maven-3.6.3', type: 'maven'
		git 'https://github.com/moganraj/HelloWorld'
	}
	stage('Compile-Package'){
		sh 'mvn package'
	}
}