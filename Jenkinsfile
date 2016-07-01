node {
    def serviceName = "vertx-examples"

    git url: "https://github.com/ricardohmon/${serviceName}.git"
    withEnv(["PATH+MAVEN=${tool 'M3'}/bin"]) {
    	sh 'mvn -B validate'
  	}
}
