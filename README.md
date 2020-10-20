# CTIS_WebApp
Web app for CTIS

Theme colour: deeppink  (#FF1493)

View wireframes here: https://balsamiq.cloud/sk0y2rn/p1sxzpr


	* CentreOfficer 

		* 
record tester

			* 
addOfficer(username, password, name, position)
	* 
Test centre

		* 
Register test centre 

			* 
addTestCentre(name) - id generated 
	* 
Test Kit 

		* 
Manage test kit stock 

			* 
addTestKit(name, quantity)  - id generated 
			* 
updateTestKit(kitID, quantity) 


	* 
CovidTest 

		* 
Record new test 

			* 
addNewPatientTest(username, password, name, patientType, symtoms, status) - test id, testdate generated, status = pending
			* 
addNewTest(username, patientType, symtoms, status) 
		* 
Update test result 

			* 
updateResult(testID, result, status) - resultDate generated, Status = completed
		* 
Generate test report 

			* 
viewTestHistory()
	* 
Patient

		* 
updatePatient(username, patientType, symtoms) 


