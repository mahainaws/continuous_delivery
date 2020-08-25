pipeline {
	agent any
	stages {
		stage("Clone_Repository") {
			steps {
				echo 'Clone is in Progress'
				sleep 4
				echo 'Clone is Completed'
			}
		}
		
		stage("Compile") {
			steps {
				echo 'Code compilation is in Progress'
				sleep 3
				echo 'Compilation is Completed'
			}
		}
		
		stage("Unit_Testing") {
			steps {
				echo 'Unit Testing is in Progress'
				sleep 7
				echo 'Unit Testing is Completed'
			}
		}
		
		stage("Integration_Testing") {
			steps {
				echo 'Integration Testing is in Progress'
				sleep 4
				echo 'Integration Testing is Completed'
			}
		}

		stage("Test_Coverage") {
			steps {
				echo 'Test Coverage in Progress'
				sleep 5
				echo 'Test Coverage is Completed'
			}
		}
		
		stage("Packaging") {
			steps {
				echo 'Packaging in Progress'
				sleep 3
				echo 'Packaging is completed'
			}
		}
		
		stage("Dev_Deploy") {
			steps {
				echo 'Dev deploy is in Progress'
				sleep 4
				echo 'Dev deploy is completed'
			}
		}
		
		stage("Smoke_Test") {
			steps {
				echo 'Smoke Test is in Progress'
				sleep 2
				echo 'Smoke Test is  successful'
			}
		}
		
		stage("Test_Deploy") {
			steps {
				echo 'Test deploy is in Progress'
				sleep 3
				echo 'Test deploy is completed'
			}
		}
		
		stage("Func_Testing") {
			steps {
				echo 'Functional Testing is started'
				sleep 7
				echo 'Functional Testing is completed'
			 }
		}
		
		stage("UAT_Deploy") {
			steps {
				echo 'UAT deploy is in Progress'
				sleep 3
				echo 'UAT deploy is completed'
			}
		}
		
		stage("UAT_Testing") {
			steps {
				echo 'UAT testing is in Progress'
				sleep 4
				echo 'UAT testing is completed'
			}
		}
		
		stage("Pre-Prod_Deploy") {
			steps {
				echo 'Pre-Prod deploy is in Progress'
				sleep 3
				echo 'Pre-Prod deploy is completed'
			}
		}
		
		stage("Performance_Testing") {
			steps {
				echo 'Performance testing is in Progress'
				sleep 5
				echo 'Performance testing is completed'
					}
				}
}
}
