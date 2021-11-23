pipeline {
	agent any
	stages {
		stage("Clone") {
			steps {
				echo 'Code is being pulled from GitHub'
				sleep 6
				echo 'Cloning is Completed..'
			}
		}
		
		stage("Compile") {
			steps {
				echo 'Code compilation is in Progress'
				sleep 5
				echo 'Compilation is Completed'
			}
		}
		
		stage("Unit Testing") {
			steps {
				echo 'Unit Testing is in Progress'
				sleep 8
				echo 'Unit Testing is Completed'
			}
		}
		
		stage("Integration Testing") {
			steps {
				echo 'Integration Testing is in Progress'
				sleep 11
				echo 'Integration Testing is Completed'
			}
		}
		
		stage("Packaging") {
			steps {
				echo 'Packaging in Progress'
				sleep 4
				echo 'Packaging is completed'
			}
		}
		
		stage("Push Artifacts") {
			steps {
				echo 'Pushing Artifacts to Nexus'
				sleep 5
				echo 'Artifcats are pushed to Nexus'
			}
		}
		
		stage("Deploy to Dev") {
			steps {
				echo 'Dev deploy is in Progress'
				sleep 4
				echo 'Dev deploy is completed'
				sh 'cp index.html /opt/tomcat/webapps/ROOT'
			}
		}
		
		stage("Smoke Test") {
			steps {
				echo 'Smoke Test is in Progress'
				sleep 2
				echo 'Smoke Test is  successful'
			}
		}
		
		stage("Deploy to Test") {
			steps {
				echo 'Test deploy is in Progress'
				sleep 3
				echo 'Test deploy is completed'
				sh 'cp index.html /opt/tomcat/webapps/ROOT'
			}
		}
		
		stage("Funcational Testing") {
			steps {
				echo 'Functional Testing is started'
				sleep 7
				echo 'Functional Testing is completed'
			 }
		}
		
		stage("DePloy to UAT") {
			steps {
				echo 'UAT deploy is in Progress'
				sleep 3
				echo 'UAT deploy is completed'
				sh 'cp index.html /opt/tomcat/webapps/ROOT'
			}
		}
		
		stage("UAT Testing") {
			steps {
				echo 'UAT testing is in Progress'
				sleep 4
				echo 'UAT testing is completed'
			}
		}
		
		stage("Deploy to Pre-Prod") {
			steps {
				echo 'Pre-Prod deploy is in Progress'
				sleep 3
				echo 'Pre-Prod deploy is completed'
				sh 'cp index.html /opt/tomcat/webapps/ROOT'
			}
		}
		
		stage("Performance Testing") {
			steps {
				echo 'Performance testing is in Progress'
				sleep 5
				echo 'Performance testing is completed'
					}
				}
}
}
