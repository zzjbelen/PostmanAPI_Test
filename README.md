# PostmanAPI_Test
##This is an API testing project using Postman.
##This will validate below testing scenarios:

	1. Check if status is not found (Status code 404)
		- Negative scenario for Url not found - it should return a status code 404
	2. Get all users 
		- Count number of users
		- Check Status code -200
		- Check JSON body
	3. Get USER
		- Check Status code -200
		- Check JSON Body
		- Check all data for specific user(user1 as example)
#Below Scenarios are expected to have a 1 failed result in Test execution.
#Expected output is only for 1 user (userid 1) but it returns all records:
	4. Get USER Albums
		- Check Status code -200
		- Check JSON body
		- Validate data
	5. Get USER Todos
		- Check Status code -200
		- Check JSON body
		- Validate data
	6. Get User Posts
		- Check Status code -200
		- Check JSON body
		- Validate data

#This is related to issue with different url (https://github.com/typicode/jsonplaceholder/issues/91)

#Framework used in this project is built in Postman.
	- Tool is simple and easy to use
	- It is an open source
	- You can create a collection for REST calls and save each call as part of collection for execution in the future

#How to run the Test
-Before running the test, you must have Postman installed in your machine.
-Once installed, you can proceed.
1. Download file in Github
	url: "https://github.com/zzjbelen/PostmanAPI_Test"
	filename:jsonprinciple.postman_collection.json
2. Open Postman application
3. Import the collection downloaded in Github 
4. Click on Runner to run the collection imported from Github.
   Collection Runner window will open.
5. In the Collection runner window, Select the Collection and add the number of iterations you want to run the test
6. Click on jsonprinciple, run results tab will open
7. You can view the Test results summary by clicking on Run Summary
   You can also export the Test Result using the Export Result button


https://github.com/zzjbelen/PostmanAPI_Test
