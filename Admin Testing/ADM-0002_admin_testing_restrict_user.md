## **ADM-0002:** Admin testing - Restrict user

> **Summary:** Verify that an admin can restrict a user. <br>

**Preconditions:**
<br/>User must be an admin. <br/>
User must be on profile page. <br/>

Scenario 1 

 | \# | Step                                                                                     | Expected Behavior | 
 |----|------------------------------------------------------------------------------------------|-------------------| 
 |  1 | Click the `User Management` button                                                                     | Verify that the `User Management` page is shown.   | 
 |  2 | Check the page                                                              | Verify that the list of registered users are displayed.   | 
 |  3 | Search the name of the user on the search box. | Verify that admin can search the name of the user they want to restrict.  | 
 |  4 | Click the combobox and select an appropriate reason for the action.    |Verify that the value reflected on the combobox is the same as teh clicked value.| 
 |  5 | Set the duration of the restriction.  |Verify that the date will be reflected on the box.| 
 |  5 | Set additional notes regarding the action on the textbox below the combobox.  |Verify that the text field value reflects the inputted text.| 
 |  6 | Click the `Confirm` button.|Verify that the user's status found in column three will show `Restricted`.| 


**Post-conditions:**  
The user can no longer participate in any thread.    


Scenario 2

 | \# | Step                                                                                     | Expected Behavior | 
 |----|------------------------------------------------------------------------------------------|-------------------| 
 |  1 | Click the `User Management` button                                                                     | Verify that the `User Management` page is shown.   | 
 |  2 | Check the page                                                              | Verify that the list of registered users are displayed.   | 
 |  3 | Search the name of the user on the search box. | Verify that admin can search the name of the user they want to restrict.  | 
 |  4 | Click the combobox and select an appropriate reason for the action.    |Verify that the value reflected on the combobox is the same as teh clicked value.| 
 |  5 | Set the duration of the restriction.  |Verify that the date will be reflected on the box.| 
 |  5 | Set additional notes regarding the action on the textbox below the combobox.  |Verify that the text field value reflects the inputted text.| 
 |  6 | Click the `Cancel` button.|Verify that the user's status will stay the same.| 


**Post-conditions:**  
None