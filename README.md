# Student_Rest_API_Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run FAIRUZ_ZAHIN_SNEHA.postman_collection.json -e FAIRUZ_ZAHIN_SNEHA.postman_environment.json
```
- Run Command for Report: 
```console 
newman run  FAIRUZ_ZAHIN_SNEHA.postman_collection.json -e FAIRUZ_ZAHIN_SNEHA.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- file:///D:/All%20course/SQA%20Course/API%20testing/API-Testing-Question.pdf

## Test Case list:
1. ### Get Student
	> Get Student Data Sets from the database.

2. ### Create Student
	> Create data sets using the dynamic variables
 
3. ### Get Specific Student
	> Get Specific Students from the database

4. ### Create Technical Skills 
	> In the test case you need to validate the following field values:
	1. > Only Message

5. ### Create a Student Address
	> In the test case you need to validate the following field values:
	1. > Only Message

6. ### Get Final Student's Details
	> In the test case you need to validate the following field values:
	1. > First Name
	2. > Middle Name
	3. > Last Name
	4. > Date of Birth
	5. > Language
	6. > Year Of Experience
	7. > Last Used Date
	8. > House Number
	9. > City
	10. > State
	11. > Country
	12. > Std Code
	13. > Home Address
	14. > Mobile

## Newman Report Summary:
![Newman Report Summary](![image](https://github.com/fairuzzahin/API_Testing_TestingWorld/assets/87386589/93efecff-6879-4684-b8a3-5610c2d89983.png))

![Newman Report Summary](https://user-images.githubusercontent.com/70250199/232209794-f84c539b-e3cf-4e80-ab0e-9d6d59b1a339.png)



