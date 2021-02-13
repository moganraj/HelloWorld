node{
/*Comment*/
//Single line Comment
//https://youtu.be/pts8zdHel5E
	stage('SCM Checkout'){
		git 'https://github.com/moganraj/HelloWorld'
	}
	stage('Compile-Package'){
		def mvnHome = tool name: 'apache-maven-3.6.3', type: 'maven'
		sh "${mvnHome}/bin/mvn package"
	}
}