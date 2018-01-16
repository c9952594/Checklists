# Deployment things

* [ ] Create release documentation
* [ ] Create any roles/users required on the server
* [ ] Desired State Configuration
	* [ ] Setup server
	* [ ] Setup windows features
	* [ ] Setup communications
		* [ ] Firewall
		* [ ] Ports
	* [ ] Setup (event) logging
* [ ] Install service 
* [ ] Run smoke tests
	* [ ] Include dependancies
		* [ ] Include test runner along with the tests
* [ ] Communications - started and stopped
* [ ] Turn off monitoring
* [ ] Handle load balancing
* [ ] Handle pools - offline/online
* [ ] Setup automated code review tools
 
# Setting up a deployment process

* [ ] If a deployment goes wrong can it be rolled back to the previous correct version?

## Testing

* [ ] How are you going to test your actual deployment without screwing up the environment you're deploying to?
* [ ] Smoke tests

## Reviews

* [ ] Has the deployment passed all required reviews?
	* [ ] Code
	* [ ] Test 
	* [ ] Documentation
	* [ ] Use release note
	* [ ] Change management
* [ ] Can review status be automatically verified?
      Is the deployment aborted if reviews aren't correct?
	
## Communications

* [ ] Does the deployment automatically notify when the process begins and finishes?

## Authorisation

* [ ] For each environment is the deployment process restricted to authorised users?
* [ ] Does the process deploy required users to local/remote systems?

## Infrastructure

## Toggles

* [ ] How are toggles handled?
* [ ] Do you need another environment to ensure toggled features are working correctly with each other?

## Multi-stage

* [ ] Does the otder of deployment matter?

## Manual

* [ ] Do you need a manual 'check' step?