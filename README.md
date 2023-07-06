This project is created to execute all api's by using rest assured below are the given features
Features-
         1-This project is capable to generate the individuals report by using static driver class 
	       >Rest-POST,PATCH,PUT
        
         2-User can also construct the request body using parameters taken from excel file.I have created an Utility using ApachePOI to read data from excel.
      	
         3-This project is build on the concept of data driven and keyword driven.
      	>I have divided project into 4 packages they are 
	  (a)Request repository-Inside this we have our Baseuri,RequestBody  and resource of our rest api method.
		(b)Test classes-In this we are parsing the requestbody,responsebody and by using the @test annotations we are genrating the allure report
		(c)Api method class-In this class we are using the given when then method to validate the response parameters.
		(d)Driver class-By using this class we are validating our result.
     
      4-The test execution is driven by static driver class.
    
      5-These project is capable of saving the evidence of the execution into text files which contains details of request sent, endpoint and response received.
