## **ADM-0001:** Admin testing - Ban user

> **Summary:** Verify that an admin can ban a user. <br>

**Preconditions:**
<br/>User must be an admin. <br/>
User must be on profile page. <br/>

Scenario 1 

 | \# | Step                                                                                     | Expected Behavior | 
 |----|------------------------------------------------------------------------------------------|-------------------| 
 |  1 | Click the `User Management` button                                                                     | Verify that the `User Management` page is shown.   | 
 |  2 | Check the page                                                              | Verify that the list of registered users are displayed.   | 
 |  3 | Search the name of the user on the search box. | Verify that admin can search the name of the user they want to ban.  | 
 |  4 | Click the combobox and select an appropriate reason for the action.    |Verify that the value reflected on the combobox is the same as teh clicked value.| 
 |  5 | Set additional notes regarding the action on the textbox below the combobox.  |Verify that the text field value reflects the inputted text.| 
 |  6 | Click the `Confirm` button.|Verify that the user's status found in column three will show `Banned`.| 


**Post-conditions:**  
The user will not be able to login on the platform.

Scenario 2

 | \# | Step                                                                                     | Expected Behavior | 
 |----|------------------------------------------------------------------------------------------|-------------------| 
 |  1 | Click the `User Management` button                                                                     | Verify that the `User Management` page is shown.   | 
 |  2 | Check the page.                                                              | Verify that the list of registered users are displayed.   | 
|  3 | Search the name of the user on the search box. | Verify that admin can search the name of the user they want to ban.  | 
 |  4 | Click the combobox and select an appropriate reason for the action.    |Verify that the value reflected on the combobox is the same as teh clicked value.| 
 |  5 | Set additional notes regarding the action on the textbox below the combobox.  |Verify that the text field value reflects the inputted text.| 
 |  6 | Click the `Cancel` button.|Verify that the user's status will stay the same.| 

**Post-conditions:**  
None.
