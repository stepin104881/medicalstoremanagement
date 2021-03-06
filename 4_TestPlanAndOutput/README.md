# **Test Plan**
## **Scope of testing**
### **In scope**

|Module Name                                                          |	Description
|---------------------------------------------------------------------|-----------------------
|Login	                                                              |    Authorized access is allowed here                               
| Purchase a medicine                                                 |	The system allows to view the if the required quantity of medicine is above or below the available       |                                                                     | quantity of medicine in the store and calculates the cost of medicine required.
| Add a medicine	                                              | The system allows adding the details of new medicine in the record.
| Delete a medicine	                                              |  The system allows deleting the details of existing medicine from the record.
|Quantity of medicine                                                 |	It displays the number of amount of medicine available in the store
|Medicine information	                                              | It displays information about medicine in the store
|Enter information of medicine                                        |	More information about the medicine can be entered by the user.


### **Out of scope**
</br>1.User interfaces
</br>2.Hardware interfaces
## **Quality objectives**
</br></br>●	Ensure the Application under Test conforms to functional and non-functional requirements.
</br>●	Bugs/issues are identified and fixed before they go live.
## **Test Methodology**
 The waterfall model is adopted as the test methodology here as it proceeds to the next phase only when the previous phase is completed.
## **Test Criteria**
### **Suspension Criteria**
 If more than 45% of test cases are failed then the testing is suspended until all fail cases are fixed
### **Exit Criteria**
</br>●	100% Test coverage.
</br>●	All manual test cases are executed.
</br>●	All open bugs are fixed or will be fixed in the next release.
## **Test Environment**
The test cases are executed in Code Blocks IDE.


# **Test Cases**
   
|Test cases|Test scenario	                                                      |Test Steps	             |Test Data   
|----------|--------------------------------------------------------------------------|------------------------------|---------------------------------------------------
| 1|	To check if the user can log in using a valid username and password |	Enter username and password  |	Username - medical_store   </br>Password- password
|2|To know if there is required quantity of medicine in the store and the cost of medicine | Choose option 1| Enter 1 and enter the quantity of medicine require.|
|3 |	To check whether able to add more info about a particular medicine    |	Choose option 2	  |  Enter 2 and enter the name of the medicine into which we need to add more info.
|    4     |	To know the info about the stock of medicine in the store	      |  Choose option 3	     |   Enter 3
|5|	To know the info about a particular medicine	 |      Choose option 4	     |   Enter 4 and enter the name of the medicine of which we need to know the information.
|    6	|To add a new medicine’s details into the record	|   Choose option 5	|   Enter 5 and enter the details of new medicine into the list.
  |  7|	To delete a medicine from the record|	Choose option 6	|Enter 6 and enter the name of the medicine which we need to delete.|
  |  8 |	To change the quantity of medicine	|Choose option 7	|Enter 7 and enter the name of the medicine of which we need to change the quantity.|
   | 9	|To exit 	||	Enter any other numbers of keys

# **Expected Results**

|Test cases|Test scenario	|Expected Results|
|----------|-----------------|-----------------------------------------|
|1	|To check if the user can log in using a valid username and password	|Successful login|
|2|To check if there is required quantity of medicine available and to know the price of medicine|It asks to enter the name of medicine which need to purchase and enter the quantity. It displays whether the quantity we mentioned is available or not and also displays the cost of medicine of the quantity we require|
|3|To check whether able to add more info about a particular medicine|	It asks to enter the name of medicine so that it displays its details and we can add more details of that medicine.
|4|To know the info about the stock of medicine in the store	|Displays the details of all the medicine in the store. The details include name, price, availability, company name, manufacturing date, expiry date, etc.|
|5|To know the info about a particular medicine|	It asks to enter the name of the medicine we want so that it displays its details.|
|6|To add a new medicine’s details into the record|	It allows us to add the details of a new medicine into the record.|
 |7|To delete a medicine from the record|	The deletion of medicine’s details can be performed.|
 | 8|	To change the quantity of medicine	|The quantity of medicine can be changed.|
 | 9|	To continue with other options|	Helps to continue with other options|
 |10|	To exit|	It exits from the program|

