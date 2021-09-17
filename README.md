
TITLE OF PROJECT :  CRUD Using JSONPowerDB

ABOUT PROJECT

![SS](https://user-images.githubusercontent.com/75634847/133783874-26f830c2-95ec-420a-a58f-0f0b3d1073c0.jpg)
 











Description:


		In this project we generally use CRUD operations on JSONPowerDB .  CRUD Stands for Create, Retrieve, Update, Delete .To perform this  CRUD operations we will require data .So we will generate the data and store it in database

To store this data to JSON  database we require the following steps 

Step 1 :  Validate the form data 
	Before validating the data we need to create the web form by using the HTML
	This form contains the data that is required to perform the CRUD operations in JSON 
	As the form contains the data for performing CRUD we need to validate this data 
	Validation generally involves keeping all the data in the form as mandatory as complete data is required to perform CRUD 
Step 2: Invoke the JPDB request 
	The data received from the form has to be inserted by using the IML HTTP Command i.e. PUT


a.	PUT  Method  :
o	This  Method  is IML[Index Manipulation Language] command
o	This Method is used to Insert Single Record in database 
o	This Method consists of the Connection-Token that is used to build a Connection with the database 
o	PUT Method uses the PUT method to create a request called createPUTRequest()
o	This method is used to create a PUT request and by using this method we insert data to JPDB
o	The createPUTRequest() consists of Connection-token,Jsonobj,dbname,rel-name

o	Connection-token is used to establish the connection with code and database 
o	Jsonobj consists of the data that we have received from the web form
o	dbname  consists of the name of database to which we want to store the data 
o	rel-name is the relation name of that database




	     
      Step 3:  Execute the request 
	Now whatever request we have created using the HTTP Command and the data received from the web-form we need to execute the request 
	To execute the request we use executeCommand() method 
	This   executeCommand() method consists of reqString,dbBaseURL,apiEndPointURL
	This Step involves the execution of the request and generating the Response
	Whatever the Response is we will get after the execution of this method Success or Fail
	Whatever data we have provided this method gives the Response for the same 


  Step 4 : Reset Form Data 
	After generating the request the response is invoked and after the invoke of the Response we need to reset the complete form for Entering the new data to the form 
	This is the last Step in the Process as it is done after invocation of the response from JPDB
	This Step to Reset the Form So that the new User can enter the data 


















Technologies Used :

1.	HTML
2.	AJAX
3.	JSONDB


1.	HTML 

	HTML (Hypertext Markup Language) is the code that is used to structure a web page and its content.
	 It is the standard text formatting language used for creating and displaying pages on the Web.
	HTML documents are made up of two things: the content and the tags that format it for proper display on pages
	This technology is used to design the web form of the project 

2.	AJAX

	Ajax is Asynchronous JavaScript and XML
	Ajax is not a Programming Language 
	The Ajax is basically Combination of :
i.	A   browser  built in the XMLHTTPRequest object : This can be used for request the data from the web server
ii.	JS and HTML DOM which is used to display or use the data 



3.	JSONDB

	JSON is javascript object notation
	It is having explosive growth in recent years and is slowly becoming the de-facto standard for data and communication 
	Any software application that needs backend database uses the JSON such as dynamic web application, mobile application, Desktop application
	This technology is best suited to real time application of data analytics


















     
BENEFITS OF USING JSONPOWERDB: 

i.JSONPowerDB is schema free so less time consuming for product development
ii.JSONPowerDB is easy to use in real time projects
iii.JSONPowerDB uses WebService API So development Cost is less
iv.JSONPowerDB  is highly secure technology as it has multiple security layers
v. JSONPowerDB builds Worlds Fastest Indexing Engine (Power Index)
vi. It has multimode database with one solution to variety of data 
vii. It uses single instance million indexes 
viii. It has best performance of server side native NOSQL.












RELEASE HISTORY:

--Initially I had to Create Github Account
--Then Create a new Repository
--Then Version the project code and then Commit the Project code
--Then Push the project code by using Github URL
--But got a error of authorization and resolve the same by generating the Access token
--Lastly the code was successfully uploaded to Github

