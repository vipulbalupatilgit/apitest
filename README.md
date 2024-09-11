**README for Executing Cartedo Postman Collection
This guide will help you set up and execute the Cartedo.postman_collection.json Postman collection. Follow these steps to import the collection into Postman and run the requests.**

**Prerequisites**
Postman Installed: Ensure you have Postman installed on your computer. You can download it from Postman’s official website.
Steps to Execute the Collection
1. Import the Collection
Open Postman.
Click on the Import button located in the top-left corner of the Postman app.
In the import window, choose the Upload Files tab.
Click the Choose Files button and select the Cartedo.postman_collection.json file from your local system.
Click the Open button to upload the file.
Postman will show a preview of the collection. Click Import to complete the process.

2. Run the Collection
Click on the Cartedo collection in the left sidebar to select it.
Click the Run button located at the top-right of the collection view.
The Postman Collection Runner will open.
Review the requests in the Collection Runner to ensure everything is set up correctly.
Click the Start Run button to execute all requests in the collection.

3. View Results
After execution, the results will be displayed in the Collection Runner window.
Review the status of each request (e.g., success, failure) and any responses received.
You can also export the results if needed by clicking the Export Results button.


**Test cases**

1- To check the list user API  https://reqres.in/api/users?page=2

 1-Verify the response 
 2-Verify the status code



2-To check the single user API https://reqres.in/api/users/2
 1-verify that single user can be fecthed via ID
 2-verify the user details
 3-Verify the status code should be 200
 4-Verify the status code when ID is wrong
 5-Verify the response when the ID is wrong


3-To check that user can create an user using POST https://reqres.in/api/users
 1-verify that user is successfuly created when the request body is correct
 2-Verify the status code should be 201 when the user is created
 3-Verify that user is not created when the request body is inncorrect
 4-Verify the status code when the request body is wrong
 5-verify the response when the request body is empty


