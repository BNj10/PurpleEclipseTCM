## **AUTH-0006:** Authentication testing - Change Password  

> **Summary:** Verify user can change password.  <br>

**Preconditions:** User must be logged in.  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage.   | Verify that the homepage is shown.   | 
 |  2 |   Click the dropdown box on the navigation bar.   |Verify that the `Profile`, `Settings`, and `Signout` button is shown.   
 |  3 |   Click `Settings` button.   |Verify that the `Settings` page is shown.   |  
 |  4 |   Provide your current password to the text box below `Current Password`.   | Verify that the text box’s value is the same as the current password.  |  
 |  5 |   Provide a new password to the text box below `New Password`. | Verify that the text box’s value is the same as the new password.  |  
 |  6 |   Type the new password again to the text box below `Confirm New Password`.  | Verify that the text box’s value is the same as the new password.  |  
 |  7  |   Click `Change Password` button   | Verify that success message is shown.   |  

**Post-conditions:**  
The account password is updated successfully.
