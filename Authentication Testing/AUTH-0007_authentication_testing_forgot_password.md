## **AUTH-0007:** Authentication testing - Forgot Password  

> **Summary:** Verify user can recover lost account.  <br>

**Preconditions:** User must have an account with a registered email address.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage                                     | Verify that the homepage is shown.             | 
 |  2 |   Click the `Login` button                               | Verify that the login form overlay is shown.   | 
 |  3 |   Click the `Forgot password` text link                  | Verify that the forgot password overlay is shown.  | 
 |  3 |   Provide the registered email address to the text box.  | Verify that the value of the text box reflects the actual inputted value.   |  
 |  3 |   Click `Send Reset Email` button.                       | Verify that the success message is shown.   |   
 |  3 |   Wait for response.                                     | Verify that an email request is received.| 

**Post-conditions:** 
The account password is updated successfully.	