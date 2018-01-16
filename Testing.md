* Reporting and documentation
	* Different stakeholders
		* Management
		* Customers
		* Regulators
	* Test reports automatically generated
		* Include results of test run on all environments
		* Include types of tests run
		* Include unit and system test report
	* Results should be archived and saved
	* Audit and tracability of release and tests
	* Tests should be documented
* Monitoring
	* Monitoring/Loggin alerting across all environments
		* Dev -> Test -> Live
	* Monitoring should be testable
		* Team is in charge of the monitoring of the product
	* Dashboards required 
* Deployment
	* Smoke tests are run automatically
		* Remove manual intervention
		* Remove need for human presents in deployments (dev/testers)
* Performance
	* Early and often
		* Against integration system test environments
		* Daily
	* Live-like environment with peak load
		* Performance Lab
		* Pre production
	* Feature toggled on
* Static Analysis
	* Done against each release
	* Fortify/Sonar
	* Metrics gathered
		* Code coverage
		* Cyclomatic complexity
		* Depth of inheritance
		* Class coupling
* Exploratory
* General
	* Quality is everyones responsibility
	* Not only the testers do testing
	* Silos should be minimised
	* Testing effort not duplicated
		* Shift left
		* Favour unit tests over integration of e2e
		* Duplicate/Unnecassary tests should be removed
	* Favour fixing broken code over development
		* Ensure adequate test coverage
	* Stop using visual studio test projects
		* Find an alternative
	* Business logic removed from DBs
* Shift Left
	* Tests run as early as possible
		* Devs machine is an environment
	* Requirements gathered early
	* Get customers involved
	* Code and test reviews carried out by the team
* Security
	* Should be carried out by the team
		* Take the ones off the final pen tests that are only carried out on major releases
	* Work closely with security
	* Pen test organised
	* Static analysis should be run each release   
* Build
	* Unit and integration tests to be run as part of the build
	* Release build against every check-in (or pull request)
	* No ignored tests
	* Fail build on failed tests
* Test Data
	* Consistent across teams and environemtns
	* Streamlined process to update or add
	* Data anomyminisation
	* Remove need for dozens of test people or users
		* Unit test coverage not duplciated e2e
* Requirements
	* Gathered early
	* Clarrified with worked examples
	* Collaboration between dev/test/PO
		* Before commencing development
	* Acceotance tests written and automated