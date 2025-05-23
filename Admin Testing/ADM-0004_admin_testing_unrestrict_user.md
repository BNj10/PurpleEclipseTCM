## **ADM-0001:** Admin testing - Ban user

> **Summary:** Verify that an admin can unrestrict a user. <br>

**Preconditions:**
<br/>User must be an admin. <br/>
The other user must be restricted. <br/>

Scenario 1 

 | \# | Step                                                                                     | Expected Behavior | 
 |----|------------------------------------------------------------------------------------------|-------------------| 
 |  1 | Click the `User Management` button                                                                     | Verify that the `User Management` page is shown.   | 
 |  2 | Check the page                                                              | Verify that the list of registered users are displayed.   | 
 |  3 | Search the name of the user on the search box. | Verify that admin can search the name of the user they want to unban.  | 
 |  4 | Click the `Restrict` button.    |Verify that the `Unrestrict User` overlay will be shown. | 
 |  5 | Click `Confirm` button.  |Verify that the status of the user becomes `Active`| 


**Post-conditions:**  
The user will be able to login on the platform.

Scenario 2

 | \# | Step                                                                                     | Expected Behavior | 
 |----|------------------------------------------------------------------------------------------|-------------------| 
 |  1 | Click the `User Management` button                                                                     | Verify that the `User Management` page is shown.   | 
 |  2 | Check the page                                                              | Verify that the list of registered users are displayed.   | 
 |  3 | Search the name of the user on the search box. | Verify that admin can search the name of the user they want to unban.  | 
 |  4 | Click the `Restrict` button.    |Verify that the `Unrestrict User` overlay will be shown. | 
 |  5 | Click `Cancel` button.  |Verify that the status of the user will stay the same.| 


**Post-conditions:**  
None